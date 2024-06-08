---
title: 'An empirical study of code smells in transformer-based code generation techniques'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Mohammed Latif Siddiq
  - Shafayat H Majumder
  - Sourov Jajodia
  -  Joanna CS Santos

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2022-10-03T00:00:00Z'
doi: '10.1109/SCAM55253.2022.00014'

# Schedule page publish date (NOT publication's date).
publishDate: '2022-10-03T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2022 IEEE 22nd International Working Conference on Source Code Analysis and Manipulation*
publication_short: In *SCAM*

abstract: Prior works have developed transformer-based language learning models to automatically generate source code for a task without compilation errors. The datasets used to train these techniques include samples from open source projects which may not be free of security flaws, code smells, and violations of standard coding practices. Therefore, we investigate to what extent code smells are present in the datasets of coding generation techniques and verify whether they leak into the output of these techniques. To conduct this study, we used Pylint and Bandit to detect code smells and security smells in three widely used training sets (CodeXGlue, APPS, and Code Clippy). We observed that Pylint caught 264 code smell types, whereas Bandit located 44 security smell types in these three datasets used for training code generation techniques. By analyzing the output from ten different configurations of the open-source fine-tuned transformer-based GPT-Neo 125M parameters model, we observed that this model leaked the smells and non-standard practices to the generated source code. When analyzing GitHub Copilot's suggestions, a closed source code generation tool, we observed that it contained 18 types of code smells, including substandard coding patterns and 2 security smell types.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Security
  - Software Engineering

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.researchgate.net/profile/Mohammed-Latif-Siddiq/publication/367100424_An_Empirical_Study_of_Code_Smells_in_Transformer-based_Code_Generation_Techniques/links/63c44136d9fb5967c2dc4e85/An-Empirical-Study-of-Code-Smells-in-Transformer-based-Code-Generation-Techniques.pdf'
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
--------
<!-- # {{% callout note %}}
# Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
# {{% /callout %}}

# {{% callout note %}}
# Create your slides in Markdown - click the _Slides_ button to check out the example.
# {{% /callout %}}

# Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->

# LJT-Homepage

Personal academic website of **Junteng Liu**, built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template (a fork of the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme) and hosted on GitHub Pages.

## About

Junteng Liu is a first-year Ph.D. candidate in the HKUST NLP Group at the Hong Kong University of Science and Technology, advised by Professor Junxian He. His research focuses on natural language processing and machine learning, including LLM reasoning and reinforcement learning, hallucination in vision-language models, and LLM truthfulness and interpretability.

## Site content

* `_pages/about.md` — homepage: bio, research interests, education, research experience, skills, publications, awards, and contact information
* `_pages/cv.md` — CV page
* `_pages/publications.html` + `_publications/` — publications
* `_config.yml` — site-wide configuration (title, author profile, contact links)
* `_data/navigation.yml` — top navigation menu

## Running locally

1. Make sure ruby-dev, bundler, and nodejs are installed.

   On most Linux distributions the command is:
   ```bash
   sudo apt install ruby-dev ruby-bundler nodejs
   ```

   On MacOS:
   ```bash
   brew install ruby
   brew install node
   gem install bundler
   ```

2. Run `bundle install` to install ruby dependencies.

3. Run `jekyll serve -l -H localhost` to build the site and serve it from `localhost:4000`.

## License

This repository is a fork of [Academic Pages](https://github.com/academicpages/academicpages.github.io), which was forked by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), © 2016 Michael Rose, released under the MIT License (see LICENSE).

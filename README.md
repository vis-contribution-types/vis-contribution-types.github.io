## Configuring site properties

Site metadata is in [_config.yml](_config.yml)

## Editing the index page

You can edit the [index.html](index.html) page here and changes will be reflected on [vis-contribution-types.github.io](https://vis-contribution-types.github.io).

## Editing the style

You can edit the style in [assets/main.scss](assets/main.scss).

## Adding example papers

Add example papers to the corresponding contribution type file under the `_contribution_types` folder. 

## Setting up a local site

To edit and preview the site locally, follow these instructions:

0. Ensure that git, Ruby, Ruby Gems, and Jekyll are installed.
1. Clone the repository: 
    ```
    git clone https://github.com/vis-contribution-types/vis-contribution-types.github.io.git
    ```

2. Install Jekyll and Bundler: 
    ```
    cd vis-contribution-types.github.io
    gem install jekyll bundler
    ```

3. Install (or update) the bundle: 
    ```bash
    bundle install
    # or bundle update
    ```

4. Run locally at [localhost:4000](http://localhost:4000): 
    ```
    bundle exec jekyll serve -P
    ```

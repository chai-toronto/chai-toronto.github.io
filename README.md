# Table of Contents
- **[Local development](#local-development)**
- **[Updating your profile](#updating-your-profile)**: `_data/members.yml`
- **[Adding a publication](#adding-a-publication)**: `_publications/paper_name.yml`

# Local Development
1. Install Ruby if it is not already on your machine.
	* Mac: Ruby is installed by default, but you may choose to update it using Homebrew or RVM. 
	* Windows: use http://rubyinstaller.org/. 
	* Linux: run `sudo apt-get install ruby-full`.
2. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` (OS X users may need to `sudo gem install github-pages`) This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
3. Clone down your fork `git clone git@github.com:chai-toronto/chai-toronto.github.io.git`
4. Serve the site and watch for markup/sass changes `jekyll serve`
5. View your website at http://127.0.0.1:4000/
6. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.

# Updating Your Profile
## Edit Metadata
Add an entry to `_data/members.yml` with the following fields:
- `id`: This should be your last name. This is what you'll use throughout the site to refer to you. If you have a website listed, it will replace references of your name with a link to your website.
- `name`: Full name
- `affiliation`: Departmental program
- `image`: Path to your profile picture. Images should be square and ideally 165x165px.
- `website`: Full link to your personal website
- `degree`: The shorthand name of your degree, such as `PhD`, `MSc`, or `BS`
- `active`: Put `true` if you are currently working in the lab or `false` if you are now working elsewhere

## Upload image
Images should be uploaded to `images/members/`. Images should be square and (ideally) 165x165px. If you upload something else, it will be cropped.

# Adding a Publication
Create a new file in `_publications/`. The file should have the following fields:
- `authors`: This should be a list of full names. If an author is a lab member (or former lab member), use the member's `id` instead of their name to link it to their website.
- `award`: (optional) The name of the award the paper received (e.g., `'Best Paper Award'` or `'Honorable Mention Award'`)
- `bibtex`: Copy from the ACM DL, not from Google.
- `caption`: This will go under the image on the project detail page.
- `citation`: Copy from the ACM DL, not from Google.
- `date`: Publication/presentation date
- `image`: Hi-res image for the project detail page (accompanies `caption`). Add to `images/pubs/`.
- `news`: (optional) List of different press releases, which contains
	- `name`: the name of the news entity
	- `url`: the url to the article
	- `headline`: the headline
	- `date`: the date the article was published
- `pdf`: Copy from the ACM DL, not anywhere else.
- `thumbnail`: Must be 16x9 and 300px wide. Add to `images/pubs/`.
- `title`: Verbatim paper title
- `venue`: Full name of the publication venue. If it is a common name, look in `_data/venues.yml` to see if a shortcut has been defined. If so, you can use the shorthand name (including the `$` delimiters) and the full name will automatically be used. You can mix shorthand names with other text if you need to specify that it was submitted to a workshop or alternative track.
- `video`: (optional) Link to external video, such as YouTube or Vimeo.
- `video_embed`: (optional) HTML embed code for video player
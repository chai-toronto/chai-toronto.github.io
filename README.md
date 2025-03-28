# Table of Contents
- **[Local development](#local-development)**
- **[Updating your profile](#updating-your-profile)**: `_data/members.yml`
- **[Adding a publication](#adding-a-publication)**: `_publications/paper_name.yml`

# Local Development
1. Follow the instructions [here](https://jekyllrb.com/docs/installation/) to install `ruby`, `jekyll`, and `bundler`
2. Clone down your fork `git clone git@github.com:chai-toronto/chai-toronto.github.io.git`
3. Serve the site and watch for markup/sass changes `bundle exec jekyll serve`
4. View your website at http://127.0.0.1:4000/
5. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.

# Updating Your Profile
Add an entry to `_data/members.yml` with the following fields:
| Field | Required | Details |
| --- | --- | --- |
| `id` | yes | Should usually be formatted as `firstname_lastname`. This is what you'll use throughout the site to refer to yourself and link to your homepage. |
| `name` | yes | First and last name | 
| `affiliation` | yes | Department |
| `degree` | yes | Degree program (`PhD`, `MSc`, or `BS`) |
| `image` | yes | Path to your profile picture within the repository. Images should be square and ideally 165x165px. |
| `website` | no | Link to your personal website |
| `gscholar` | no | ID associated with your Google Scholar profile (`{id}` in `https://scholar.google.com/citations?user={id}`) |
| `linkedin` | no | ID associated with your LinkedIn profile (`{id}` in `https://www.linkedin.com/in/{id}`) |
| `twitter` | no | ID associated with your Twitter/X profile (`{id}` in `https://x.com/{id}`) |
| `twitter` | no | ID associated with your BlueSky profile (`{id}` in `https://bsky.app/profile/{id}`) |
| `coadvisor` | no | The name or `id` of your cosupervisor |
| `active` | yes | `true` if you are currently working in the lab or `false` if you are now working elsewhere |
| `search` | no | Indicates that you are looking for new positions (`industry`, `academia`, `postdoc`, `grad_school`) |

# Adding a Current Project
Create a new file in `_projects/`. The file should have the following fields:
| Field | Required | Details |
| --- | --- | --- |
| `title` | yes | Publication title |
| `lead` | yes | List of student leads, using `id` when available |
| `date` | yes | Publication date |
| `thumbnail` | yes | Path of thumbnail image in `images/projects/`that is ideally 16x9 and 300px wide |
| `category` | yes | Relevant research themes (`Active Sensing`, `Passive Sensing`, or `Design`) |
| `health_topic` | no | Relevant health topic. Please refer to options already in the website before creating a new one |
| `device` | no | Relevant technology being studied. Please refer to options already in the website before creating a new one |
| `skills` | yes | Relevant skills being used. Please refer to options already in the website before creating a new one |

# Adding a Publication
Create a new file in `_publications/`. The file should have the following fields:
| Field | Required | Details |
| --- | --- | --- |
| `title` | yes | Publication title |
| `authors` | yes | List of student leads, using `id` when available |
| `venue` | yes | Full name of the publication venue. If it is a common name, look in `_data/venues.yml` to see if a shortcut has been defined. If so, you can use the shorthand name (including the `$` delimiters) and the full name will automatically be used. You can mix shorthand names with other text if you need to specify that it was submitted to a workshop or alternative track. |
| `date` | yes | Publication date |
| `link` | yes | External link to the ACM DL or equivalent |
| `thumbnail` | yes | Path of thumbnail image in `images/pubs/`that is ideally 16x9 and 300px wide |
| `award` | no | Name of the award the paper received (e.g., `'Best Paper Award'`, `'Honorable Mention Award'`) |
| `abstract` | yes | Copy from the ACM DL or equivalent when possible, otherwise use Google Scholar. |
| `video_embed` | no | HTML embed code for video player |
| `news` | no | List of different press releases, which contains <ul><li>`name`: the name of the news entity</li><li>`url`: the url to the article</li><li>`headline`: the headline</li><li>`date`: the date the article was published</li></ul> |
| `category` | yes | Relevant research themes (`Active Sensing`, `Passive Sensing`, or `Design`) |
| `health_topic` | no | Relevant health topic. Please refer to options already in the website before creating a new one |
| `device` | no | Relevant technology being studied. Please refer to options already in the website before creating a new one |
| `skills` | yes | Relevant skills being used. Please refer to options already in the website before creating a new one |

# Uploading Images
Images should be uploaded to `images/members/`. Images should be square and (ideally) 165x165px. If you upload something else, it will be cropped.

# Journal

Hugo-based system for writing, organizing, and analysis of my personal journal entries. This repository includes the theme, all required scripts, and a few sample entries. Obviously I won't be placing my personal entries in this repository.

**Why?** My Github academic discount has expired, and I can no longer publish github pages sites for private repositories. Thus, personal information must be scrubbed from all private repositories, history must be deleted, and my journal needs to be moved to a serve-from-localhost system.

Metrics and analysis of posts will be integrated at a later date, utilizing *D3* for visuals.

## Installation

1. Download the zip and copy the contents into a new private repository.
2. Install **Hugo** and **vim**, though the system can be easily modified to use your editor of choice.
3. Add the `globalscripts` folder to your `PATH`. (GNU/Linux/Unix only.)

## Usage

- `je` can be called from anywhere to add a new daily file if one does not exist, add a new timestamp, and place the cursor in the correct location for the user to begin a new entry.
- `jv` can be called from anywhere to spin up the hugo site locally and open the configured browser to the homepage.

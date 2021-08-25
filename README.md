# nbdev_doc_automation
Segregated base repository for building and deploying nbdev documentation through one GemFile and dependency


**Files that Need Adjusting**:
- `docs/_data/topnav.yml` needs to adjust the `external_url` to be the git url from the `settings.ini` file in the original repo

**Files needed in the original repo**:
- `docs/_config.yml`
- `docs/sidebar.json`*
  If no sidebar is present, build it ourselves which will happen when we run `nbdev_build_docs`

Everything else should have the ability to be automatically built. 

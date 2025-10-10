# From Data to Discovery: Machine Learning for Dynamical Systems

Workshop at ICLR 2026

For the published page, please see TBC (site will be published once the workshop is accepted).

## Development/updates

If you want to edit this site:

- Main page: Edit [./docs/source/index.rst](./docs/source/index.rst)
- Schedule: Edit [./docs/source/schedule.rst](./docs/source/schedule.rst)
    - Schedule itself is generated from the data in [./docs/source/schedule.csv](./docs/source/schedule.csv)
- Accepted papers: Edit [./docs/source/papers.rst](./docs/source/papers.rst)
    - Papers are listed in [./docs/source/papers.csv](./docs/source/papers.csv)
- Organizers: Edit [./docs/source/organizers.html](./docs/source/organizers.html)
    - Organizer photos are in [./docs/source/_static/organizers](./docs/source/_static/organizers)
- Speakers: Edit [./docs/source/speakers.html](./docs/source/speakers.html)
    - Speaker photos are in [./docs/source/_static/speakers](./docs/source/_static/speakers)

To build the site locally:

```bash
./build_docs.sh
```

Each change merged to `main` will be automatically deployed to the published site.

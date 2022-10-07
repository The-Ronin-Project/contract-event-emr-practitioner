# EMR Practitioner

# Scope
This represents a Practitioner in the EMR service. This is derived from the RoninPractitioner resource in the Ronin Common Data Model as defined [here](https://supreme-garbanzo-99254d0f.pages.github.io/ig/Ronin-Implementation-Guide-Home-List-Profiles-Ronin-Practitioner.html).

# Usage
This contains a simple `Makefile` for automating validation and document generation.  
- `make test`: Validate each versioned schema against all of its example files.
- `make doc`: Compile human readable HTML documentation for each versioned schema
- `make clean`: Cleans up all generated files

# Links
- [Event Contract Management Standard](https://projectronin.atlassian.net/wiki/spaces/ENG/pages/1797521454/Event+Contract+Management+Standard)
- [Ronin Event Standard](https://projectronin.atlassian.net/wiki/spaces/ENG/pages/1748041738/Ronin+Event+Standard)
- [Event Topic Standards](https://projectronin.atlassian.net/wiki/spaces/ENG/pages/1765998701/Event+Topic+Standards)
- [Event Contract Tooling Docker Image](https://github.com/projectronin/ronin-contract-event-tooling)
- [Event Contract CI/CD Workflow](https://github.com/projectronin/github/blob/event_contract_cicd/.github/workflows/event_contract_cicd.yaml)

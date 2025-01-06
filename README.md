# Self Hosted Keycloak

This project is created to expand the understanding of the IDAM tool Keycloak and understand how the tool can be selfhosted in a home server or in a scalable environment.

This is part of my personal learning stack for this year *__2025__*.

> __Note__: [Keycloak.org Guides](https://www.keycloak.org/guides) has almost all the guidance needed for setting up a self hosted instance of keycloak.

You can get up and running with docker in a minute with the keycloak provided documentation

## Scope

Create an independent self hosted version of keycloak for users management, social account authentication, Customisable login, signup, otp, and magic link based user validation for home server suitable applications. 

Some Example application to try out with are 

- [jellyfin](https://jellyfin.org/)
- [minio](https://www.min.io/)
- [mealie](https://mealie.io/)
- [xwiki](https://www.xwiki.org/xwiki/bin/view/Main/)

## Project Structure

``` bash
selfhosted_keycloak_idam/
│
├── README.md                       # High-level overview of the project and setup
│
├── docs/                           # Documentation directory for project
│
├── config/                         # Configuration templates for keycloak
│
├── scripts/                        # Helpful automation and setup scripts
│
├── tests/                          # Test configurations and scripts
│
└── .gitignore                      # Git ignore file to exclude 
```

## Notes

A deep dive in to my thought process and notes is in my [Thoughts_and_Notes.md](/Thoughts_and_Notes.md)

## License

[MIT License](/License.txt)

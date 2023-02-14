# How to contribute

Contributing in the Gaia-X-dases working group for xAPI is mainly about writing profiles.
The profile definition and documentation is run between a bunch of profile.

Follow this guideline to get access to all the tools, and start writing xAPI!

## Join community tools

1. You should get access to the Gaia-X working group on the ADLNET server. 
    - [Create an account](https://profiles.adlnet.gov/user/create) or [sign in](https://profiles.adlnet.gov/user/login) on the ADLNET server. 
    - Ask to join the [Gaia-X Data Space for Education and Skills (DASES)](https://profiles.adlnet.gov/organization/e8c5169e-3b55-45e5-a03f-8ec20f4db1a0) working group.

2. You should get access to the Gaia-X organisation on Github. 
    - Create an account or sign in on Github. 
    - Ask to join the [Gaia-X organisation](https://github.com/orgs/gaia-x-dases/) on the Prometheus slack. A member will then add you as a collaborator in the organisation.

## Propose or update a profile

### Design on the ADLNET server

1. On [the Gaia-X working group profile page](https://profiles.adlnet.gov/organization/e8c5169e-3b55-45e5-a03f-8ec20f4db1a0), select the profile you want to work on or create a new one.
    - :warning: When creating a new profile, select the `Use an external IRI` option and use the following pattern: `http://schema.dases.eu/xapi/profile/{name_of_the_profile}
    - :warning: When creating new concepts, select the `Use an external IRI` option and use the following patterns depending on the concept types.

| **Concept type** | **IRI pattern** |
|---|---|
| extensions | https://w3id.org/xapi/{name_of_the_profile}/extension/{name_of_the_concept} |

### Export on the Github organisation profiles' repositories

Once you have finished you work session on the ADLNET server and you want your work to be discussed with other group members, you have to update the documentation on the Github repository of the corresponding xAPI profile.

1. Export the profile jsonld file directly from the web page of the profile on the ADLNET server (It is used to keep the latest version of the profile on the Github documentation)

#### The xAPI profile repository already exists

2. open a pull request on the Github repository of the profile, by updating the existing content with your modification)
3. Ask for reviews from group members (by assigning them or asking for voluntary reviews on Slack)
 
#### The xAPI profile repository does not exist

2. Create a new one if it does not exist (use the [xAPI template repository](https://github.com/gaia-x-dases/xapi-profile-template) of the organisation and follow the instruction with the content created on the ADLNET server) 
3. Notify group members of the existence of the profile, so that they can open pull request to review your work.


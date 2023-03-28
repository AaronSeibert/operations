# Why am I doing this... again?
I never end up keeping up with infrastructure maintenance as I stray too far from the initial provisioning image,
and no way to figure out what's changed since the first "oh shit, it runs!"

- [ ] BUILD THE FOUNDATION FIRST
    - [ ] CI/CD should be able to deploy everything, both internal network and external network
    - [ ] Some sort of bootstrap is going to be necessary
        - [ ] Public github repo
        - [ ] Download and install Bitwarden
        - [ ] Retrieve an item that contains the necessary information to access cloud object storage
            - What steps are necessary for this?
        - [ ] There are more steps to fill in
    - [ ] DO NOT MOVE ON TO THE NEXT THING WITHOUT A TEST SUITE FOR EACH FEATURE
    - [ ] Try to eliminate SPOF. 
    - [ ] I saved some pages in Drafts. Convert those in to this doc.
    - [ ] Document Document Document. I do kinda like wiki.js
    - [ ] Document the git workflow we're using. TL;DR; version here with link to the actual project documentation
    - [ ] Everything should have a readme
        - [ ] Define the template.
        - [ ] Individual tech stacks should be able to build their level of template with whatever utilities available.
                For example, helm-docs I'm used to. 
        - [ ] Each "directory" should basically be a pretty-looking directory listing. Basically, we're going to
                figure out how wiki.js does the git import, and we'll need a pipeline that pulls all of the readme
                files (each directory should have a readme file
    - [ ] Use git modules as necessary. Just be sure to account for them in the pipeline and TEST TEST TEST DOCUMENT
            DOCUMENT DOCUMENT
    - [ ] The foundation is the build pipeline. Once it's built, once the readmes and documentation publish are automated,
            once the build successfully passes the tests, then we merge it in to master and kick off a pipeline to deploy
    - [ ] USE UNIT TESTS 
    - [ ] Small tasks man. Small sub-features. Don't overwhelm yourself, and commit often. Like, after every function or section
            is written and documented. Speaking of, go commit this and go to bed.

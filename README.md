# circleci-orb-coveralls
Fix coveralls not to rely on sudo if $EUID is not 0

https://circleci.com/developer/orbs/orb/coveralls/coveralls

https://github.com/coverallsapp/orb/issues/10

https://circleci.com/docs/2.0/orb-author-validate-publish/

https://github.com/coverallsapp/orb

## Release

    circleci orb validate orb.yml
    
    circleci orb publish orb.yml solven/coveralls@0.0.2
# ts-buildpack

This is a simple buildpack to install typescript globally on heroku and then link it to the current project.

The buildpack assumes that nodejs has been installed already by an upstream buildpack.The buildpack also shortcuts detection and always runs if it is enabled.


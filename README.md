# update-spfx-webpart-ids
A GULP script to shift SPFx WebPart Id's by increasing the last character (e.g. 1 --> 2, 9 --> a, c --> d, z --> 0). The purpose is to use this as a part of an automated build/deployment (for example VSTS) in order to automatically create an alternative test package from all the web parts to be used in a development environment.

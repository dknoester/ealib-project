template
========

This is a template for EALib-compatible projects.  It is designed to live "alongside" a clone of EALib.  For example, you should do something like this:

    % git clone https://github.com/dknoester/ealib.git ealb
    % git clone https://github.com/dknoester/ealib-project.git <project name>

Issuing a build command (either via bjam or the template.xcworkspace from within your project directory) should then build EALib and your executable.

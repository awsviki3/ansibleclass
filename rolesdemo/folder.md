    defaults:
    =========
     contains default variables for the role. Variables in default have the lowest priority so they are easy to override.

    vars:
    ====
     contains variables for the role. Variables in vars have higher priority than variables in defaults directory.

    tasks:
    =========
     contains the main list of steps to be executed by the role.

    files:
    =========
     contains files which we want to be copied to the remote host. We don’t need to specify a path of resources stored in this directory.

    templates:
    =========
     contains file template which supports modifications from the role. We use the Jinja2 templating language for creating templates.
     
    meta:
    =========
     contains metadata of role like an author, support platforms, dependencies.
    handlers: contains handlers which can be invoked by “notify” directives and are associated with service.
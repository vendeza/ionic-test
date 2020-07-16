- Go to your new project: cd ./<project>
- Run ionic serve within the app directory to see your app in the browser
- Run ionic capacitor add to add a native iOS or Android project using Capacitor
- Generate your app icon and splash screens using cordova-res --skip-config
  --copy
- Explore the Ionic docs for components, tutorials, and more:
  https://ion.link/docs
- Building an enterprise app? Ionic has Enterprise Support and Features:
  https://ion.link/enterprise-edition

yarn run build
ionic serve
ionic capacitor run <platform>

# Usage:

    $ ionic <command> [<args>] [--help] [--verbose] [--quiet] [--no-interactive] [--no-color] [--confirm] [options]

# Global Commands:

    completion ...................... (experimental) Enables tab-completion for Ionic CLI commands.
    config <subcommand> ............. Manage CLI and project config values (subcommands: get, set, unset)
    docs ............................ Open the Ionic documentation website
    info ............................ Print project, system, and environment information
    init ............................ (beta) Initialize existing projects with Ionic
    login ........................... Log in to Ionic
    logout .......................... Log out of Ionic
    signup .......................... Create an Ionic account
    ssh <subcommand> ................ Commands for configuring SSH keys (subcommands: add, delete, generate, list,
                                      setup, use)
    start ........................... Create a new project

# Project Commands:

    build ........................... Build web assets and prepare your app for any platform targets
    capacitor <subcommand> .......... Capacitor functionality (subcommands: add, build, copy, open, run, sync,
                                      update) (alias: cap)
    cordova <subcommand> ............ Cordova functionality (subcommands: build, compile, emulate, platform, plugin,
                                      prepare, requirements, resources, run) (alias: cdv)
    deploy <subcommand> ............. (paid) Appflow Deploy functionality (subcommands: add, build)
    doctor <subcommand> ............. Commands for checking the health of your Ionic project (subcommands: check,
                                      list, treat)
    enterprise <subcommand> ......... (paid) Manage Ionic Enterprise features (subcommands: register)
    generate ........................ Automatically create framework features (alias: g)
    git <subcommand> ................ (paid) Commands relating to managing Appflow git (subcommands: remote)
    integrations <subcommand> ....... Manage various integrations in your app (subcommands: disable, enable, list)
                                      (aliases: i, integration)
    link ............................ Connect local apps to Ionic
    package <subcommand> ............ (paid) Appflow package functionality (subcommands: build, deploy)
    repair .......................... Remove and recreate dependencies and generated files
    serve ........................... Start a local dev server for app dev/testing (alias: s)
    ssl <subcommand> ................ (experimental) Commands for managing SSL keys & certificates (subcommands:
                                      generate)

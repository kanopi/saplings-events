# Saplings-Events Repository

## Overview

Welcome to the Saplings-Events repository, the central hub for managing everything Events within the Saplings application. Saplings-Events handles the Events content type, Event taxonomies, Event views, and Event schema. This repository coordinates with several sub-repositories to handle different aspects of content creation and management.

## Sub-Repositories:

1. **[kanopi/saplings-content-base](https://github.com/kanopi/saplings-content-base)**
   - Contains base fields and configurations for all content types in Saplings.

   a. **[kanopi/saplings-media](https://github.com/kanopi/saplings-media)**
      - Handles Media entities and implements best practices configurations.
         - **[kanopi/imagemagick-configuration](https://github.com/kanopi/imagemagick-configuration)**
            - Configuration files for Imagemagick integration within Saplings.

   b. **[kanopi/saplings-theme](https://github.com/kanopi/saplings-theme)**
      - Configures the UI Patterns Suite, including modules and themes.
         - **[kanopi/saplings_child](https://github.com/kanopi/saplings_child) [Theme]**
            - Custom base theme, a child of the Ui Suite Bootstrap Contrib theme.
              
   c. **[kanopi/saplings_custom](https://github.com/kanopi/saplings_custom) [Module]**
            - Contributed module with utility commands.

2. **[kanopi/saplings-content-types](https://github.com/kanopi/saplings-content-types)**
   - Handles content types.
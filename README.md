# Flying Camp Design - KiCad Project Templates

## Setup Instructions

The following instructions will configure KiCad to use the Flying Camp Design project templates.

### Environment Variable Setup

Open the `Configure Paths` dialog from the `Preferences` menu and update the environment variable for the user templates directory (add it if it doesn't exist):

| **Name**                | **Path**                     |
| ----------------------- | ---------------------------- |
| KICAD_USER_TEMPLATE_DIR | /path/to/fcd-kicad-templates |

Make sure these changes are saved in the `kicad_common` user preferences file (you may need to restart KiCad for the changes to be saved).  You should see a new environment variable in the `[EnvironmentVariables]` section of the file:

```
[EnvironmentVariables]
KICAD_USER_TEMPLATE_DIR=/path/to/fcd-kicad-templates
```

### Using Project Templates

To create a new project from one of the Flying Camp Design project templates, choose `File` -> `New` -> `Project from Template…`.  In the `Project Template Selector` window, select the `User Templates` tab and choose from one of the template options.


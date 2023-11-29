# openedx-theme
## Steps to setup the theme in OpenEdx

1. Follow the instructions in the Indigo repository to install it ([Indigo theme](https://github.com/overhangio/tutor-indigo)).
2. Once installed it, replace the folder 'themes' with this one ([new 'theme' folder](https://drive.google.com/file/d/14RRN5Eu0YyMyHZiSHj2TZxznfOGrL0xN/view?usp=sharing)).
    1. Path of the 'theme' folder <config_root>/env/build/openedx 
4. Run the following commands to apply the changes:

   1. ```bash
      tutor images build openedx
      ```
   2. ```bash
      tutor local start -d
      ```

## Useful commands
- Print the config root of tutor
```bash
      tutor config printroot  
```

# Generamba Catalog

Catalog of [Generamba](https://github.com/rambler-digital-solutions/Generamba) templates.

# How to use

1. Install and setup Generamba
2. Update ```Rambafile``` catalogs and templates list:
```
### Templates
catalogs:
- 'https://github.com/viveron/generamba-catalog'
templates:
- {name: [TEMPLATE_NAME]}
```
3. Run ```generamba template install``` for obtain templates
4. Run ```generamba gen [MODULE_NAME] [TEMPLATE_NAME] --module_path [PATH]``` to generate template module at specific path if you use the same paths both in the filesystem and Xcode

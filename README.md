# generamba-templates

This is template catalog for [Generamba](https://github.com/strongself/Generamba).

## Set up

1. Install generamba.

    ```yaml:Gemfile
    gem "generamba"
    ```
    
    ```
    $ bundle install
    ```
    
2. generate a configuration file.

    ```
    $ bundle exec generamba setup
    ```


## Usage of templates

1. Add templates to `Rambafile` .

    ```yaml:Rambafile
    ### Templates
    catalogs:
    - 'https://github.com/AkihiroShiraishi/generamba-templates'
    templates:
    - {name: ws_swiftui_viper}
    ```

2. Run `generamba template install` .

3. Run `generamba gen [Module name] [Tempalate name]` .

## Templates

- ws_swiftui_viper


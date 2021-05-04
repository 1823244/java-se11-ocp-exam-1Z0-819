# Localization

## Locale

- `Locale.getDefault()`
- `getDisplayCountry()`
- `getDisplayLanguage()`
- `getDisplayVariant()`
- `getDisplayName()`
- `getLanguage()`
- `getCountry()`
- `getVariant()`

## Locale.Builder

- `Locale.Builder().setLanguage("de").setCountry("DE").build()`


## ResourceBundle

- `ResourceBundle.getBundle("someName", locale)`

## Resource Bundle Properties File

```
my.msg = Hello
another.key = Bye
```

Name File | Key | Value
------ | ------ | --------
Bundle.properties      | my.msg | Hello   
Bundle_fr.properties   | my.msg | Bonjour   
Bundle_de.properties   | my.msg | Hallo   
Bundle_en.properties   | my.msg | Hello   
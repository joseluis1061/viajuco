# Viajuco

Angular CLI version 18.0.1. 
NPM version 20.13.1

## Instalar
Descargue el proyecto y ejecute npm install

## Development server

Ejecuta `ng serve` para un hambiente de desarrollo. Navegue a `http://localhost:4200/`

## Build

Ejecuta `ng build` para construir el proyecto en el directorio de salida `\dist`

## Estructura del proyecto

src/
├── app/
│   ├── features/
│   │   ├── web/
│   │   │   ├── home/
│   │   │   ├── product-catalog/
│   │   │   └── product-detail/
│   │   └── admin/
│   │       ├── dashboard/
│   │       ├── product-management/
│   │       └── user-management/
│   ├── layouts/
│   │   ├── web-layout/
│   │   └── admin-layout/
│   ├── shared/
│   │   ├── components/
│   │   │   ├── shared-button/
│   │   │   ├── shared-input/
│   │   │   ├── shared-form-field/
│   │   │   ├── shared-card/
│   │   │   ├── shared-data-table/
│   │   │   ├── shared-navigation/
│   │   │   ├── shared-layout/
│   │   │   ├── ...
│   │   ├── services/
│   │   ├── models/
│   │   ├── guards/
│   │   └── interceptors/
│   └── app.component.ts
├── assets/
├── environments/
└── styles/
│   ├── global/
│   │   ├── _variables.scss
│   │   ├── _mixins.scss
│   │   ├── _typography.scss
│   │   └── _reset.scss
│   ├── themes/
│   │   ├── _light-theme.scss
│   │   └── _dark-theme.scss
│   ├── utilities/
│   │   ├── _spacing.scss
│   │   ├── _colors.scss
│   │   └── _responsive.scss
│   └── main.scss

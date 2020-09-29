# Symfony 5 Certification Guide

## Beginner level

### Before you start Symfony

HTTP

##### Symfony and HTTP Fundamentals

* Documentation [Symfony and HTTP Fundamentals](https://symfony.com/doc/5.0/introduction/http_fundamentals.html)

##### Method

* Documentation [Method](https://tools.ietf.org/html/rfc2616#section-5.1.1)

##### Status Code

* Documentation [Status-Line](https://tools.ietf.org/html/rfc2616#section-6.1)
* Documentation [Status Code Definitions](https://tools.ietf.org/html/rfc2616#section-10)

PHP

##### Classes and Objects

* Documentation [The Basics](https://php.net/manual/en/language.oop5.basic.php)
* Documentation [Properties](https://php.net/manual/en/language.oop5.properties.php)
* Documentation [Class Constants](https://php.net/manual/en/language.oop5.constants.php)
* Documentation [Constructors and Destructors](https://php.net/manual/en/language.oop5.decon.php)
* Documentation [Visibility](https://php.net/manual/en/language.oop5.visibility.php)
* Documentation [Object Inheritance](https://php.net/manual/en/language.oop5.inheritance.php)
* Documentation [Object Interfaces](https://php.net/manual/en/language.oop5.interfaces.php)
* Documentation [Objects and references](https://php.net/manual/en/language.oop5.references.php)
* Documentation [Scope Resolution Operator (::)](https://php.net/manual/en/language.oop5.paamayim-nekudotayim.php)
* Documentation [OOP Changelog](https://www.php.net/manual/en/language.oop5.changelog.php)

##### Namespaces

* Documentation [Namespaces](https://php.net/manual/en/language.namespaces.php)
* Video [Namespaces on SymfonyCasts](https://symfonycasts.com/screencast/php-namespaces-in-120-seconds/namespaces)

### Discover Symfony

Symfony Architecture

##### Code organization

* Documentation [The Architecture](https://symfony.com/doc/5.0/quick_tour/the_architecture.html)

##### The Symfony Components

* Documentation [The Symfony Components](https://symfony.com/doc/5.0/components/index.html)

##### Symfony Roadmap

* Documentation [Symfony Roadmap](https://symfony.com/roadmap)

##### Setup

* Documentation [Installing & Setting up the Symfony Framework](https://symfony.com/doc/5.0/setup.html)

##### Managing Dependencies With Symfony Flex

* Documentation [Symfony Flex](https://symfony.com/doc/5.0/setup/flex.html)

##### License

* Documentation [License](https://symfony.com/doc/5.0/contributing/code/license.html)

### Symfony controllers for beginners

Controllers

##### The Request

* Documentation [\"Request -> Controller -> Response\" lifecycle](https://symfony.com/doc/5.0/components/http_kernel.html#the-workflow-of-a-request)
* Documentation [Request usage](https://symfony.com/doc/5.0/components/http_foundation.html#request)
* Source Code [Request class source code](https://github.com/symfony/symfony/blob/4.0/src/Symfony/Component/HttpFoundation/Request.php)

##### The Response

* Documentation [Response usage](https://symfony.com/doc/5.0/components/http_foundation.html#response)
* Source Code [Response class source code](https://github.com/symfony/symfony/blob/4.0/src/Symfony/Component/HttpFoundation/Response.php)

##### Controller

* Documentation [Symfony's front controller](https://symfony.com/doc/5.0/create_framework/front_controller.html)
* Documentation [Creating a web page](https://symfony.com/doc/5.0/page_creation.html)
* Documentation [Symfony's controller](https://symfony.com/doc/5.0/controller.html)
* Source Code [Symfony's base controller class code](https://github.com/symfony/symfony/blob/master/src/Symfony/Bundle/FrameworkBundle/Controller/AbstractController.php)

##### Controller best practices

* Documentation [Controllers best practices](https://symfony.com/doc/5.0/best_practices/controllers.html)

Routing

##### Base routing usage

* Documentation [Route configuration (YAML, XML, PHP & annotations)](https://symfony.com/doc/5.0/routing.html#creating-routes)

##### Localized routes i18n

* Documentation [Creating localized routes](https://symfony.com/doc/5.0/routing.html#localized-routes-i18n)

##### Generate URL parameters

* Documentation [Generating urls](https://symfony.com/doc/5.0/routing.html#generating-urls)

### Twig for beginners

Templating with Twig

##### Loops and conditions

* Documentation [`for` loop](https://twig.symfony.com/doc/tags/for.html)
* Documentation [Control structures](https://twig.symfony.com/doc/templates.html#control-structure)

##### Template includes

* Documentation [Include templates in your Symfony application](https://symfony.com/doc/5.0/templates.html#including-templates)
* Documentation [`include` twig function reference](https://twig.symfony.com/doc/2.x/tags/include.html)

##### Templating inheritance

* Documentation [Template layouts](https://symfony.com/doc/5.0/templating.html#template-inheritance-and-layouts)
* Documentation [Template inheritance](https://twig.symfony.com/doc/templates.html#template-inheritance)
* Documentation [`extends` tag in Twig](https://twig.symfony.com/doc/tags/extends.html)

### Create services

Dependency Injection basics

##### Dependency Injection basics

* Documentation [Types of Injection](https://symfony.com/doc/5.0/service_container/injection_types.html)

##### Register Services and Parameters

* Documentation [Introduction to Parameters](https://symfony.com/doc/5.0/configuration.html#configuration-parameters)
* Documentation [Environment variables](https://symfony.com/doc/5.0/configuration.html#configuration-based-on-environment-variables)
* Documentation [How to Import Configuration Files/Resources](https://symfony.com/doc/5.0/service_container/import.html)
* Documentation [How to Make Service Arguments/References Optional](https://symfony.com/doc/5.0/service_container/optional_dependencies.html)

### Form for beginners

Create a Simple Form

##### Forms

* Documentation [Forms](https://symfony.com/doc/5.0/forms.html)
* Documentation [Form Types Reference](https://symfony.com/doc/5.0/reference/forms/types.html)

Rendering of a Form

##### How to Control the Rendering of a Form

* Documentation [How to Control the Rendering of a Form](https://symfony.com/doc/5.0/form/form_customization.html)

Upload Files

##### How to Upload Files

* Documentation [How to Upload Files](https://symfony.com/doc/5.0/controller/upload_file.html)

### Translations basics

Translations

##### Translations

* Documentation [Translations](https://symfony.com/doc/5.0/translation.html)

##### Locale

* Documentation [How to Work with the User's Locale](https://symfony.com/doc/5.0/translation/locale.html)

### Validation basics

Validation

##### The Basics of Validation

* Documentation [Validation](https://symfony.com/doc/5.0/validation.html)
* Documentation [Constraints Reference](https://symfony.com/doc/5.0/reference/constraints.html)

### Console for beginners

Symfony built-in commands

##### Built-in commands

* Documentation [Using built-in commands](https://symfony.com/doc/5.0/components/console/usage.html)

Custom commands

##### Custom commands

* Documentation [Creating a custom console command](https://symfony.com/doc/5.0/console.html#creating-a-command)

##### Configuration

* Documentation [Handling console arguments](https://symfony.com/doc/5.0/components/console/console_arguments.html)

##### Options and arguments

* Documentation [Using command-line arguments](https://symfony.com/doc/5.0/console/input.html#using-command-arguments)
* Documentation [Using command-line options (like `-f`)](https://symfony.com/doc/5.0/console/input.html#using-command-options)

## Intermediate level

### Intermediate usage of the Service Definitions

More with Service Definitions

##### Autowiring

* Documentation [Autowiring](https://symfony.com/doc/5.0/service_container.html#the-autowire-option)

##### Method calls

* Documentation [Method calls](https://symfony.com/doc/5.0/service_container/calls.html)

##### Synthetic services

* Documentation [Method calls](https://symfony.com/doc/5.0/service_container/synthetic_services.html)

##### Alias

* Documentation [Aliasing](https://symfony.com/doc/5.0/service_container/alias_private.html#aliasing)

##### Non shared services

* Documentation [How to Define Non Shared Services](https://symfony.com/doc/5.0/service_container/shared.html)

CompilerPass

##### CompilerPass

* Documentation [How to Work with Service Tags](https://symfony.com/doc/5.0/service_container/tags.html)
* Documentation [How to Work with Compiler Passes in Bundles](https://symfony.com/doc/5.0/service_container/compiler_passes.html)

### Intermediate usage of Forms

Data transformers

##### Data Transformers

* Documentation [How to Use Data Transformers](https://symfony.com/doc/5.0/form/data_transformers.html)

Validation Groups

##### Advanced usage of Validation Groups

* Documentation [How to Define the Validation Groups to Use](https://symfony.com/doc/5.0/form/validation_groups.html)
* Documentation [How to Choose Validation Groups Based on the Clicked Button](https://symfony.com/doc/5.0/form/button_based_validation.html)
* Documentation [How to Choose Validation Groups Based on the Submitted Data](https://symfony.com/doc/5.0/form/data_based_validation.html)
* Documentation [How to Disable the Validation of Submitted Data](https://symfony.com/doc/5.0/form/disabling_validation.html)

Custom Form Field Type

##### Custom Form Field Type

* Documentation [How to Create a Custom Form Field Type](https://symfony.com/doc/5.0/form/create_custom_field_type.html)

Form Themes

##### Form Themes

* Documentation [How to Customize Form Rendering](https://symfony.com/doc/5.0/form/form_customization.html)
* Documentation [How to Work with Form Themes](https://symfony.com/doc/5.0/form/form_themes.html)

### Debug Translations

Debug Translations

##### Debug Translations

* Documentation [How to Find Missing or Unused Translation Messages](https://symfony.com/doc/5.0/translation/debug.html)

## Advanced level

### Advanced usage of Forms

Embed Forms

##### Embed Forms

* Documentation [How to Embed Forms](https://symfony.com/doc/5.0/form/embedded.html)
* Documentation [How to Embed a Collection of Forms](https://symfony.com/doc/5.0/form/form_collections.html)

Form Events

##### Form Events

* Documentation [Form Events](https://symfony.com/doc/5.0/form/events.html)
* Documentation [How to Dynamically Modify Forms Using Form Events](https://symfony.com/doc/5.0/form/dynamic_form_modification.html)

Form Type Extension

##### Form Type Extension

* Documentation [How to Create a Form Type Extension](https://symfony.com/doc/5.0/form/create_form_type_extension.html)

### Advanced usage of the Service Definitions

Service Definitions

##### Configurator

* Documentation [How to Configure a Service with a Configurator](https://symfony.com/doc/5.0/service_container/configurators.html)

##### Parent Services

* Documentation [How to Manage Common Dependencies with Parent Services](https://symfony.com/doc/5.0/service_container/parent_services.html)

##### Lazy Services

* Documentation [Lazy Services](https://symfony.com/doc/5.0/service_container/lazy_services.html)

##### How to Decorate Services

* Documentation [How to Decorate Services](https://symfony.com/doc/5.0/service_container/service_decoration.html)

##### Inject Values Based on Complex Expressions

* Documentation [How to Inject Values Based on Complex Expressions](https://symfony.com/doc/5.0/service_container/expression_language.html)

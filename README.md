# Telosys 3 Persistence PHP Template

A [Telosys](https://telosys.org) template of a PHP Persistence for a PHP MVC application, able to perform CRUD (Create, Read, Update, Delete) operations.
All data is cache-persisted.
This template is part of a Bundle (see the Telosys 3 MVC PHP Template and Telosys 3 REST API PHP Template).
## Requirements

- PHP.

## Dependencies

- A PHP MVC Application.

## Usage

1. Download the template.  
2. Check that your model is ready (DSL/Database).
3. Generate the code with Telosys.  
4. Use the generated code in your project.

## Getting started
 
1. After being generated, this template provides you with a repository file for every entity present in your model (see "Usage:2").
2. You can import each file in their corresponding Controller like this :  
```
$this->EntityRepository = EntityRepository::getInstance();
```
NOTE : You don't need to do this if you also use the Telosys 3 MVC PHP Template.

## License

This project uses the [LGPL v3 License](https://www.gnu.org/licenses/lgpl-3.0.en.html).

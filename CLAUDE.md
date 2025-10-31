
<!-- start: Packmind standards -->
# Packmind Standards

Before starting your work, make sure to review the coding standards relevant to your current task.

Always consult the sections that apply to the technology, framework, or type of contribution you are working on.

All rules and guidelines defined in these standards are mandatory and must be followed consistently.

Failure to follow these standards may lead to inconsistencies, errors, or rework. Treat them as the source of truth for how code should be written, structured, and maintained.

## Standard: Tests redaction

Apply good practices for test redaction in **/*.spec.ts files using single expectations, assertive titles, and nested describe blocks for workflows to improve test clarity and maintainability during the development and testing of TypeScript applications. :
* Tests have a single expectation
* Tests have an assertive title and do not start with should
* Tests that show a workflow uses multiple describe to nest steps

Full standard is available here for further request: [Tests redaction](.packmind/standards/tests-redaction.md)

## Standard: Typescript code standards

Adopt TypeScript code standards by prefixing interfaces with "I" and abstract classes with "Abstract" across all *.ts files to enhance code readability and maintain consistent naming conventions when developing and maintaining TypeScript applications. :
* Prefix abstract classes with Abstract
* Prefix interfaces with I
* Use Type for plain objects, Interface when implmentation is required

Full standard is available here for further request: [Typescript code standards](.packmind/standards/typescript-code-standards.md)
<!-- end: Packmind standards -->
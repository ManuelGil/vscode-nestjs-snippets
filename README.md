# NestJS Snippets

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/imgildev.vscode-nestjs-snippets-extension?style=for-the-badge&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/imgildev.vscode-nestjs-snippets-extension?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)
[![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/imgildev.vscode-nestjs-snippets-extension?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)
[![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/imgildev.vscode-nestjs-snippets-extension?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension&ssr=false#review-details)
[![GitHub Repo stars](https://img.shields.io/github/stars/ManuelGil/vscode-nestjs-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-nestjs-snippets)
[![GitHub license](https://img.shields.io/github/license/ManuelGil/vscode-nestjs-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-nestjs-snippets/blob/main/LICENSE)

> Fast, TypeScript-first NestJS snippets for VS Code — controllers, modules, providers, GraphQL, JWT, WebSockets, testing, and more with smart placeholders and scopes.

## Overview

This Visual Studio Code extension provides a large collection of TypeScript-focused snippets for NestJS development. Use them to scaffold controllers, services, modules, decorators, GraphQL types/resolvers, authentication helpers, guards, pipes, interceptors, and test setups quickly and consistently.

## Requirements

- Visual Studio Code 1.46.0 or later

## Installation

1. Open Visual Studio Code.
2. Open the **Extensions** view (`Ctrl+Shift+X` / `⌘+Shift+X`).
3. Search for **NestJS Snippets** or install directly from the [Marketplace page](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension).
4. Click **Install** and reload the editor if prompted.

## Usage

Type part of the snippet prefix and press `Tab` or `Enter` to expand.

> Note: GraphQL operation snippets (query, mutation, subscription, fragment, type, interface) are scoped to `.graphql` files.
> Note: The `ValidationPipe` snippet defaults to `{ whitelist: true, transform: true }`.

### Selected snippets

| Snippet                                        | Purpose                               |
| ---------------------------------------------- | ------------------------------------- |
| `ns_class_controller`                          | Scaffold a controller class           |
| `ns_class_service`                             | Scaffold a service class              |
| `ns_class_module`                              | Scaffold a module                     |
| `ns_class_dynamic_module`                      | Scaffold a dynamic module             |
| `ns_class_create_dto` / `ns_class_update_dto`  | DTO classes                           |
| `ns_create_param_decorator`                    | `createParamDecorator(...)`           |
| `ns_deco_controller`                           | `@Controller()`                       |
| `ns_deco_injectable`                           | `@Injectable()`                       |
| `ns_deco_get` / `ns_deco_post` / `ns_deco_put` | HTTP method decorators                |
| `ns_deco_use_guards`                           | `@UseGuards()`                        |
| `ns_deco_use_interceptors`                     | `@UseInterceptors()`                  |
| `ns_deco_use_pipes`                            | `@UsePipes()`                         |
| `ns_deco_sse`                                  | `@Sse()`                              |
| `ns_deco_websocket_gateway`                    | `@WebSocketGateway()`                 |
| `ns_deco_subscribe_message`                    | `@SubscribeMessage()`                 |
| `ns_class_guard`                               | `implements CanActivate`              |
| `ns_class_interceptor`                         | `implements NestInterceptor`          |
| `ns_class_pipe`                                | `implements PipeTransform`            |
| `ns_new_validation_pipe`                       | `new ValidationPipe(...)`             |
| `ns_test`                                      | Testing scaffold (Jest)               |
| `ns_graphql_module_for_root`                   | `GraphQLModule.forRoot(...)` (Apollo) |
| `ns_graphql_query` / `ns_graphql_mutation`     | GraphQL operation snippets            |
| `ns_jwt_module_register`                       | `JwtModule.register(...)`             |
| `ns_jwt_service_sign`                          | `JwtService.sign(...)`                |
| `ns_app_enable_cors`                           | `app.enableCors()`                    |
| `ns_app_listen`                                | `app.listen(...)`                     |

## Contributing

Contributions to the NestJS Snippets are welcome and appreciated. To contribute:

1. Fork the [GitHub repository](https://github.com/ManuelGil/vscode-nestjs-snippets-extension).
2. Create a new branch for your feature or fix:

   ```bash
   git checkout -b feature/your-feature
   ```

3. Make your changes, commit them, and push to your fork.
4. Submit a Pull Request targeting the `main` branch.

Before contributing, please review the [Contribution Guidelines](https://github.com/ManuelGil/vscode-nestjs-snippets-extension/blob/main/CONTRIBUTING.md) for coding standards, testing, and commit message conventions. If you encounter a bug or wish to request a new feature, please open an Issue.

## Changelog

For a complete list of changes, see the [CHANGELOG.md](https://github.com/ManuelGil/vscode-nestjs-snippets-extension/blob/main/CHANGELOG.md).

## Authors

- **Manuel Gil** - _Owner_ - [@ManuelGil](https://github.com/ManuelGil)

For a complete list of contributors, please refer to the [contributors](https://github.com/ManuelGil/vscode-nestjs-snippets-extension/contributors) page.

## Follow Me

- **GitHub**: [![GitHub followers](https://img.shields.io/github/followers/ManuelGil?style=for-the-badge\&logo=github)](https://github.com/ManuelGil)
- **X (formerly Twitter)**: [![X Follow](https://img.shields.io/twitter/follow/imgildev?style=for-the-badge\&logo=x)](https://twitter.com/imgildev)

## Other Extensions

- **[Auto Barrel](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-auto-barrel)**
  Automatically generates and maintains barrel (`index.ts`) files for your TypeScript projects.

- **[Angular File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-angular-generator)**
  Generates boilerplate and navigates your Angular (9→20+) project from within the editor, with commands for components, services, directives, modules, pipes, guards, reactive snippets, and JSON2TS transformations.

- **[NestJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-generator)**
  Simplifies creation of controllers, services, modules, and more for NestJS projects, with custom commands and Swagger snippets.

- **[NestJS Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)**
  Ready-to-use code patterns for creating controllers, services, modules, DTOs, filters, interceptors, and more in NestJS.

- **[T3 Stack / NextJS / ReactJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nextjs-generator)**
  Automates file creation (components, pages, hooks, API routes, etc.) in T3 Stack (Next.js, React) projects and can start your dev server from VSCode.

- **[Drizzle ORM Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-drizzle-snippets)**
  Collection of code snippets to speed up Drizzle ORM usage, defines schemas, migrations, and common database operations in TypeScript/JavaScript.

- **[CodeIgniter 4 Spark](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-spark)**
  Scaffolds controllers, models, migrations, libraries, and CLI commands in CodeIgniter 4 projects using Spark, directly from the editor.

- **[CodeIgniter 4 Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-snippets)**
  Snippets for accelerating development with CodeIgniter 4, including controllers, models, validations, and more.

- **[CodeIgniter 4 Shield Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)**
  Snippets tailored to CodeIgniter 4 Shield for faster authentication and security-related code.

- **[Mustache Template Engine - Snippets & Autocomplete](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-mustache-snippets)**
  Snippets and autocomplete support for Mustache templates, making HTML templating faster and more reliable.

## Recommended Browser Extension

For developers who work with `.vsix` files for offline installations or distribution, the complementary [**One-Click VSIX**](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb) extension is recommended, available for both Chrome and Firefox.

> **One-Click VSIX** integrates a direct "Download Extension" button into each VSCode Marketplace page, ensuring the file is saved with the `.vsix` extension, even if the server provides a `.zip` archive. This simplifies the process of installing or sharing extensions offline by eliminating the need for manual file renaming.

- [Get One-Click VSIX for Chrome &rarr;](https://chromewebstore.google.com/detail/imojppdbcecfpeafjagncfplelddhigc?utm_source=item-share-cb)
- [Get One-Click VSIX for Firefox &rarr;](https://addons.mozilla.org/es-ES/firefox/addon/one-click-vsix/)

## License

This project is licensed under the **MIT License**. See the [LICENSE](https://github.com/ManuelGil/vscode-nestjs-snippets-extension/blob/main/LICENSE) file for full details.

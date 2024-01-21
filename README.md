# NestJS Snippets for VSCode Editor

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/imgildev.vscode-nestjs-snippets-extension?style=for-the-badge&label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/imgildev.vscode-nestjs-snippets-extension?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)
[![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/imgildev.vscode-nestjs-snippets-extension?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)
[![Visual Studio Marketplace Rating](https://img.shields.io/visual-studio-marketplace/r/imgildev.vscode-nestjs-snippets-extension?style=for-the-badge&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension&ssr=false#review-details)
[![GitHub Repo stars](https://img.shields.io/github/stars/ManuelGil/vscode-nestjs-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-nestjs-snippets)
[![GitHub license](https://img.shields.io/github/license/ManuelGil/vscode-nestjs-snippets?style=for-the-badge&logo=github)](https://github.com/ManuelGil/vscode-nestjs-snippets/blob/main/LICENSE)

This extension for Visual Studio Code adds snippets for NestJS Framework in VSCode editor. Now you can create your NestJS applications even faster.

## Requirements

- VSCode 1.46.0 or later

## Usage

### Snippets

![snippets](https://raw.githubusercontent.com/ManuelGil/vscode-nestjs-snippets/main/docs/images/snippets.gif)

Type part of snippet, press `Tab` or `Enter`, and the snippet unfolds. Below is a list of the most important shortcuts.

| Snippet | Purpose |
| --- | --- |
| ns_class_controller | class Controller |
| ns_class_exception | class Exception |
| ns_enum | enum |
| ns_class_create_dto | class CreateDto |
| ns_class_update_dto | class UpdateDto |
| ns_create_param_decorator | createParamDecorator |
| ns_class_module | class Module |
| ns_class_dynamic_module | class DynamicModule |
| ns_class_service | class Service |
| ns_class_jwt_strategy | class JwtStrategy |
| ns_class_jwt_guard | class JwtGuard |
| ns_class_jwt_service | class JwtService |
| ns_test | testing |
| ns_deco_catch | @Catch |
| ns_deco_controller | @Controller |
| ns_deco_injectable | @Injectable |
| ns_deco_optional | @Optional |
| ns_deco_use_guards | @UseGuards |
| ns_deco_use_interceptors | @UseInterceptors |
| ns_deco_use_pipes | @UsePipes |
| ns_deco_version | @Version |
| ns_deco_header | @Header |
| ns_deco_http_code | @HttpCode |
| ns_deco_redirect | @Redirect |
| ns_deco_render | @Render |
| ns_deco_post | @Post |
| ns_deco_get | @Get |
| ns_deco_delete | @Delete |
| ns_deco_put | @Put |
| ns_deco_patch | @Patch |
| ns_deco_options | @Options |
| ns_deco_head | @Head |
| ns_deco_all | @All |
| ns_deco_search | @Search |
| ns_deco_request | @Request |
| ns_deco_response | @Response |
| ns_deco_next | @Next |
| ns_deco_ip | @Ip |
| ns_deco_session | @Session |
| ns_deco_uploaded_file | @UploadedFile |
| ns_deco_uploaded_files | @UploadedFiles |
| ns_deco_headers | @Headers |
| ns_deco_query | @Query |
| ns_deco_body | @Body |
| ns_deco_param | @Param |
| ns_deco_host_param | @HostParam |
| ns_deco_req | @Req |
| ns_deco_res | @Res |
| ns_deco_sse | @Sse |
| ns_deco_global | @Global |
| ns_deco_module | @Module |
| ns_throw_bad_gateway_exception | throw BadGatewayException |
| ns_throw_bad_request_exception | throw BadRequestException |
| ns_throw_conflict_exception | throw ConflictException |
| ns_throw_forbidden_exception | throw ForbiddenException |
| ns_throw_gateway_timeout_exception | throw GatewayTimeoutException |
| ns_throw_gone_exception | throw GoneException |
| ns_throw_http_version_not_supported_exception | throw HttpVersionNotSupportedException |
| ns_throw_im_a_teapot_exception | throw ImATeapotException |
| ns_throw_internal_server_error_exception | throw InternalServerErrorException |
| ns_throw_method_not_allowed_exception | throw MethodNotAllowedException |
| ns_throw_misdirected_exception | throw MisdirectedException |
| ns_throw_not_acceptable_exception | throw NotAcceptableException |
| ns_throw_not_found_exception | throw NotFoundException |
| ns_throw_not_implemented_exception | throw NotImplementedException |
| ns_throw_payload_too_large_exception | throw PayloadTooLargeException |
| ns_throw_precondition_failed_exception | throw PreconditionFailedException |
| ns_throw_request_timeout_exception | throw RequestTimeoutException |
| ns_throw_service_unavailable_exception | throw ServiceUnavailableException |
| ns_throw_unauthorized_exception | throw UnauthorizedException |
| ns_throw_unprocessable_entity_exception | throw UnprocessableEntityException |
| ns_throw_unsupported_media_type_exception | throw UnsupportedMediaTypeException |
| ns_new_validation_pipe | new ValidationPipe |
| ns_class_exception_filter | class ExceptionFilter |
| ns_class_guard | implements CanActivate |
| ns_class_interceptor | implements NestInterceptor |
| ns_class_pipe | implements PipeTransform |
| ns_class_middleware | implements NestModule |
| ns_class_adapter | implements WebSocketAdapter |
| ns_class_logger | implements LoggerService |
| ns_config_module_for_root | ConfigModule.forRoot |
| ns_config_module_for_feature | ConfigModule.forFeature |
| ns_app_set_global_prefix | app.setGlobalPrefix |
| ns_app_get_global_prefix | app.getGlobalPrefix |
| ns_app_get_io_adapter | app.getIoAdapter |
| ns_app_use_global_pipes | app.useGlobalPipes |
| ns_app_use_global_filters | app.useGlobalFilters |
| ns_app_use_global_interceptors | app.useGlobalInterceptors |
| ns_app_use_global_guards | app.useGlobalGuards |
| ns_app_get_global_request_guards | app.getGlobalRequestGuards |
| ns_app_get_http_adapter | app.getHttpAdapter |
| ns_app_init | app.init |
| ns_app_connect_microservice | app.connectMicroservice |
| ns_app_get_http_server | app.getHttpServer |
| ns_app_use_body_parser | app.useBodyParser |
| ns_app_enable_cors | app.enableCors |
| ns_app_listen | app.listen |
| ns_app_use_web_socket_adapter | app.useWebSocketAdapter |
| ns_deco_args_type | @ArgsType |
| ns_deco_args | @Args |
| ns_deco_context | @Context |
| ns_deco_directive | @Directive |
| ns_deco_extensions | @Extensions |
| ns_deco_field | @Field |
| ns_deco_hide_field | @HideField |
| ns_deco_info | @Info |
| ns_deco_input_type | @InputType |
| ns_deco_interface_type | @InterfaceType |
| ns_deco_mutation | @Mutation |
| ns_deco_object_type | @ObjectType |
| ns_deco_query | @Query |
| ns_deco_resolve_field | @ResolveField |
| ns_deco_resolve_property | @ResolveProperty |
| ns_deco_resolve_reference | @ResolveReference |
| ns_deco_resolver | @Resolver |
| ns_deco_scalar | @Scalar |
| ns_deco_subscription | @Subscription |
| ns_graphql_module_for_root | GraphQLModule.forRoot |
| ns_graphql_upper_directive_transformer | upperDirectiveTransformer |
| ns_graphql_transform_schema | transformSchema |
| ns_graphql_build_schema_options | buildSchemaOptions |
| ns_jwt_module_register | JwtModule.register |
| ns_jwt_module_register_async | JwtModule.registerAsync |
| ns_jwt_service_sign | JwtService.sign |
| ns_jwt_service_sign_async | JwtService.signAsync |
| ns_passport_module_register | PassportModule.register |
| ns_passport_module_register_async | PassportModule.registerAsync |
| ns_deco_websocket_gateway | @WebSocketGateway |
| ns_deco_websocket_server | @WebSocketServer |
| ns_deco_subscribe_message | @SubscribeMessage |
| ns_deco_connected_socket | @ConnectedSocket |

## Connect with me

[![GitHub followers](https://img.shields.io/github/followers/ManuelGil?style=for-the-badge&logo=github)](https://github.com/ManuelGil)
[![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/imgildev?style=for-the-badge&logo=x)](https://twitter.com/imgildev)

## Other Extensions

- [NestJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-generator)
- [NestJS Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nestjs-snippets-extension)
- [Angular File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-angular-generator)
- [T3 Stack / NextJS / ReactJS File Generator](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-nextjs-generator)
- [CodeIgniter 4 Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-snippets)
- [CodeIgniter 4 Shield Snippets](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-shield-snippets)
- [CodeIgniter 4 Spark](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-codeigniter4-spark)
- [Moodle Pack](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-moodle-snippets)
- [Mustache Template Engine - Snippets & Autocomplete](https://marketplace.visualstudio.com/items?itemName=imgildev.vscode-mustache-snippets)

## Changelog

See [CHANGELOG.md](./CHANGELOG.md)

## Authors

- **Manuel Gil** - _Owner_ - [ManuelGil](https://github.com/ManuelGil)

See also the list of [contributors](https://github.com/ManuelGil/vscode-nestjs-snippets/contributors) who participated in this project.

## License

NestJS Snippets for VSCode is licensed under the MIT License - see the [MIT License](https://opensource.org/licenses/MIT) for details.

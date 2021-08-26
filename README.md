# Потрясающий Drupal на русском
Сборник модулей, рецептов и статей на русском языке

[Русскоязычный Чат по Drupal](https://t.me/drupal_rus)

## Мультязычность

## Темизация

## SEO
* [metatag](https://www.drupal.org/project/metatag) - базовый модуль для установки **любых** мета-тегов
## Формы

## Поля
* [maxlength](https://www.drupal.org/project/maxlength) - позволяет устанавливать максимальное количество символов для текстового поля. Имеет подсчёт оставшегося количества символов на JS
* [weight](https://www.drupal.org/project/weight) - добавляет тип поля "вес", с виджетом, как вес таксономии. Также добавляет поле перетаскивания элементов для views, которое можно использовать в табличном отображении. Не забудье в качестве критерия сортировки выставить вес.
* [fivestar](https://www.drupal.org/project/fivestar) - поле рейтинга в виде 5 звёзд или других виджетов. Позволяет пользователям голосовать за материал. Также предоставляет возможность оценивать связанную сущность, например, если отзывы реализованы через комментарии, то оценка, выставленная при комментировании агрегируется на связанном материалею
* [single_image_formatter](https://www.drupal.org/project/single_image_formatter) - позволяет выводить только первое изображение во множественных полях. Также поддерживает media и responsive_image

## Views
* [views_parity_row](https://www.drupal.org/project/views_parity_row) - позволяет комбинировать разные view modes в одном представлении.
* [other_view_filter](https://www.drupal.org/project/other_view_filter) - позволяет исключить строки (материалы, юзеров, etc) одного представления из другого

## Алиасы (ЧПУ)
* [subpathauto](https://www.drupal.org/project/subpathauto) - позволяет создавать алиасы для параметризованных роутов, например, user/**1**/contact > user/admin/contact
* [Drupal 8: Inbound и Outbound Processor](https://niklan.net/blog/183) - статья Никиты Малышева о расширенном управлении ЧПУ через API

## Поиск
* [search_api_ranges](https://www.drupal.org/project/search_api_ranges) - виджет диапазона для Search API, например, для интернет-магазина, позволяет создавать фильтры "От и До"

## Контактные формы
* [webform](https://www.drupal.org/project/webform) - мощнейший модуль для создания любых контактных форм, анкет и опросников
* [antibot](https://www.drupal.org/project/antibot) - модуль для защиты от спама через любые формы на сайте. Основное преимущество - модуль совершенно незаметен для обычных пользователей, при этом очень эффективен против ботов.

## Работа с содержимым
* [taxonomy_manager](https://www.drupal.org/project/taxonomy_manager) - позволяет массово создавать термины с иерархией из текстового списка. Также показывает древовидную структуру словаря, где все ветви изначально свёрнуты, что очень удобно при работе с очень большими словарями.

## Статистика
[events_log_track](https://www.drupal.org/project/events_log_track) - логирование всех действий (создание, обновление, удаление) с сущностями: меню, материалы, таксономия, пользователи и их авторизации, файлы, медиа, процессы

## Сборки

## Законодательство
* [fz152](https://www.drupal.org/project/fz152) - помогает следовать федеральному закону №152. Добавляет галочку "я даю согласие на обработку персональных данных" к любой вашей форме.

## Обновление и миграция

## Для разработчика
### Deployment

## Ждут описания
* https://www.drupal.org/project/entity_browser
* https://www.drupal.org/project/advagg
* https://www.drupal.org/project/feeds (проверить работоспособность на D8/D9)
* https://www.drupal.org/project/responsive_menu
* https://www.drupal.org/project/food_delivery_profile (сборка)
* https://www.drupal.org/project/views_field_view
* https://www.drupal.org/project/menu_item_extras
* https://www.drupal.org/project/drupalmoduleupgrader
* https://www.drupal.org/project/facetapi_pretty_paths
* https://www.drupal.org/project/migrate_process_inline_images
* https://www.drupal.org/project/viewerjs
* https://www.drupal.org/project/pdf
* https://www.drupal.org/project/pdf_reader
* https://www.drupal.org/project/views_autorefresh + https://www.drupal.org/project/views_autorefresh_d8
* https://www.drupal.org/project/default_content
* https://www.drupal.org/project/ulogin
* https://www.drupal.org/project/login
* https://www.drupal.org/project/entityreference_filter
* https://www.drupal.org/project/social_auth_vk
* https://www.drupal.org/project/optimizedb
* https://www.drupal.org/project/views_conditional
* https://www.drupal.org/project/block_field
* https://www.drupal.org/project/views_exclude_previous
* https://www.drupal.org/project/other_view_filter
* https://www.drupal.org/project/commerce_cart_redirection
* https://www.drupal.org/project/node_manager
* https://www.drupal.org/project/contentimport
* https://www.drupal.org/project/fences
* https://www.drupal.org/project/fullcalendar
* https://www.drupal.org/project/brussels_calendar
* https://www.drupal.org/project/calendar_systems
* https://www.drupal.org/project/calendar
* https://www.drupal.org/project/field_image_tooltips
* https://www.drupal.org/project/examples
* https://www.drupal.org/project/entity_extra_field
* https://www.drupal.org/project/entity_field_token
* https://www.drupal.org/project/views_tree
* https://www.drupal.org/project/entity_hierarchy
* https://www.drupal.org/project/twig_field
* https://www.drupal.org/project/page_manager
* https://www.drupal.org/project/views_field_formatter
* https://www.drupal.org/project/views_data_export
* https://www.drupal.org/project/commerce_license
* https://www.drupal.org/project/select_or_other
* https://www.drupal.org/project/booking_timeslots
* https://www.drupal.org/project/resource_booking
* https://www.drupal.org/project/bat
* https://www.drupal.org/project/graphql_twig
* https://www.drupal.org/project/ajax_links_api
* https://www.drupal.org/project/commerce_autosku
* https://www.drupal.org/project/commerce_migrate
* https://www.drupal.org/project/file_mdm
* https://www.drupal.org/project/image_effects
* https://www.drupal.org/project/taxonomy_menu_ui
* https://www.drupal.org/project/snippet_manager
* https://www.drupal.org/project/node_revision_delete
* https://www.drupal.org/project/ses_mailer
* https://www.drupal.org/project/library_manager
* https://www.drupal.org/project/autogrow
* https://www.drupal.org/project/facets
* https://www.drupal.org/project/views_entity_form_field
* https://www.drupal.org/project/billing
* https://www.drupal.org/project/transaction
* https://www.drupal.org/project/userpoints
* https://www.drupal.org/project/views_raw_sql
* https://www.drupal.org/project/focal_point
* https://www.drupal.org/project/cmlapi
* https://www.drupal.org/project/block_visibility_groups
* https://www.drupal.org/project/views_bulk_operations
* https://www.drupal.org/project/field_pager
* https://www.drupal.org/project/phpmailer
* https://www.drupal.org/project/twig_tweak
* https://www.drupal.org/project/smsframework
* https://www.drupal.org/project/smsru
* https://www.drupal.org/project/phone_number
* https://www.drupal.org/project/fullcalendar
* https://www.drupal.org/project/critical_css
* https://www.drupal.org/project/bootbase
* https://www.drupal.org/project/styleguide
* https://www.drupal.org/project/metatag_routes
* https://www.drupal.org/project/legal
* https://www.drupal.org/project/ckeditor_uploadimage
* https://www.drupal.org/project/ckeditor_pasteimage
* https://www.drupal.org/project/node_view_permissions
* https://www.drupal.org/project/view_unpublished
* https://www.drupal.org/project/pdf_reader
* https://www.drupal.org/project/trailing_slash
* https://www.drupal.org/project/pluginreference
* https://www.drupal.org/project/feeds
* https://www.drupal.org/project/ebt_tabs
* https://www.drupal.org/project/tome
* https://www.drupal.org/project/commerce_cdek
* https://www.drupal.org/project/views_arg_entity_field
* https://www.drupal.org/project/asset_injector
* https://www.drupal.org/project/dc_cart_ajax
* https://www.drupal.org/project/views_field_view
* https://www.drupal.org/project/s3fs
* https://www.drupal.org/project/panels
* https://www.drupal.org/project/no_admin_destination_redirect
* https://www.drupal.org/project/node_limit
* https://www.drupal.org/project/smtp
* https://www.drupal.org/project/draggableviews
* https://www.drupal.org/project/theme_breakpoints_js
* https://www.drupal.org/project/ueditor
* https://www.drupal.org/project/landingpage
* https://www.drupal.org/project/radix
* https://www.drupal.org/project/field_permissions
* https://www.drupal.org/project/bootstrap_sass
* https://www.drupal.org/project/bootstrap_barrio
* https://www.drupal.org/project/bootstrap
* https://www.drupal.org/project/module_builder
* https://www.drupal.org/project/httpswww
* https://www.drupal.org/project/submitted_by
* https://www.drupal.org/project/yandex_yml
* https://www.drupal.org/project/entity_usage
* https://www.drupal.org/project/domain_group
* https://www.drupal.org/project/pagerer
* https://www.drupal.org/project/scn
* https://www.drupal.org/project/no_autocomplete
* https://www.drupal.org/project/field_limiter
* https://www.drupal.org/project/upgrade_rector
* https://www.drupal.org/project/twigsuggest
* https://www.drupal.org/project/happy_new_year
* https://www.drupal.org/project/node_revision_delete
* https://www.drupal.org/project/login_emailusername
* https://www.drupal.org/project/mail_login
* https://www.drupal.org/project/login_onlyemail
* https://www.drupal.org/project/warmer
* https://www.drupal.org/project/slick
* https://www.drupal.org/project/owlcarousel
* https://www.drupal.org/project/nivo_slider
* https://www.drupal.org/project/flexslider
* https://www.drupal.org/project/conditional_fields
* https://www.drupal.org/project/taxonomy_based_visibility
* https://www.drupal.org/project/views_templates
* https://www.drupal.org/project/http2_server_push
* https://www.drupal.org/project/ckeditor_colorbox_inline
* https://www.drupal.org/project/content_entity_builder
* https://www.drupal.org/project/menu_export
* https://www.drupal.org/project/viewfield
* https://www.drupal.org/project/entity_reference_uuid
* https://www.drupal.org/project/cookiebot
* https://www.drupal.org/project/views_infinite_scroll
* https://www.drupal.org/project/fac
* https://www.drupal.org/project/finder
* https://www.drupal.org/project/suggestion
* https://www.drupal.org/project/suggestion
* https://www.drupal.org/project/search_autocomplete
* https://www.drupal.org/project/commerce_marketplace
* https://www.drupal.org/project/openlucius
* https://www.drupal.org/project/transliterate_filenames
* https://www.drupal.org/project/empty_fields
* https://www.drupal.org/project/ulogin
* https://www.drupal.org/project/social_login
* https://www.drupal.org/project/composerize
* https://www.drupal.org/project/autologout

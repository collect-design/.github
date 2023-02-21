# Collect.Design

## Components

| Name       | Purpose                                                                                            | Communication |
| ---------- | -------------------------------------------------------------------------------------------------- | ------------- |
| api        | Main repository for the authenticated api that contains the core functionalities of collect.design | HTTP          |
| app        | User facing authenticated paid app that allows users to collect their own designs                  | HTTP          |
| figma      | User facing Figma plugin that allows clients to import collected design into Figma                 | HTTP          |
| notifier   | Internal tool to send emails and notifications to users                                            | Kafka         |
| screenshot | Internal tool to screenshot websites                                                               | Kafka         |
| site-info  | Internal tool to retrieve basic site infos as well as its fonts, categories, colors, etc.          | Kafka         |
| web        | Main website for collect.design                                                                    | HTTP          |
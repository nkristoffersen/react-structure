| Container                      | layout                                               | Component                             |
|--------------------------------|------------------------------------------------------|---------------------------------------|
| Logic                          | Layout stying only                                   | Component stying                      |
| API calls                      | Imports layouts, components, containers              | Does not care where component is used |
| Redux calls                    | No logic                                             | Does not talk to redux                |
| Translation calls              | Only passing props between components and containers | Does not talk to translation          |
| Imports layouts and containers |                                                      | Focused on resuse                     |
|                                |                                                      | imports other components only         |

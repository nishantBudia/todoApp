# TODO app

This app demonstrates basic crud functionality with springboot and bean creation and usage

## Entities

| Todo               |    
|--------------------|
| Integer todoId     |
| String todoName    |
| boolean todoStatus |

## Controller
### Mappings
| Type   | Data                                                     | Endpoint            |
|--------|----------------------------------------------------------|---------------------|
| POST   | Request body - Todo                                      | todo                |
| GET    | -                                                        | todos               |
| PUT    | Path Variable - Integer id, Request Param - boolean flag | todo/id/{id}/status |
| DELETE | Path Variable - Integer id                               | todo/id/{id}        |

## Data Source

ArrayList as a bean


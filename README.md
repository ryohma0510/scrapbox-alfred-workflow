# scrapbox-alfred-workflow

This workflow enables you to actions below on Google Chrome.

Actions are implemented by JXA(JavaScript for AppleScript).

- create new page
- copy scrapbox link to clipboard
- create bookmark page

## Installation

1. install workflow package into alfred
2. set environment variables

environment variables

| name         | example      | description                                           |
| :----------- | :----------- | :---------------------------------------------------- |
| bookmark_tag | my-bookmarks | tag name for bookmarkd pages created by this workflow |
| project_name | my-notebook  | your scrapbox project name                            |

![image](https://user-images.githubusercontent.com/24651683/175785891-550c72e2-3ba2-4384-81b0-6e88e4218531.png)


## Usage

commands

| command                | description                                                                                                 |
| :--------------------- | :---------------------------------------------------------------------------------------------------------- |
| sb new <new page name> | create new scrapbox page                                                                                    |
| sb url                 | convert active chrome tab url to scrapbox form url like "[page_tile \| https://...]", and copy to clipboard |
| sb bookmark            | creage bookmark page of active chrome tab                                                                   |

### sb new

![new](https://user-images.githubusercontent.com/24651683/175786477-d9e1a4f1-48ff-4b5d-80bc-e69c01d265df.gif)


### sb url

![url](https://user-images.githubusercontent.com/24651683/175786826-e2bc6c0a-5c0f-4c73-baf7-c0d92765bcee.gif)

### sb bookmark

![bookmark](https://user-images.githubusercontent.com/24651683/175786912-e78f367f-08d7-4f34-a858-7e232ef72606.gif)

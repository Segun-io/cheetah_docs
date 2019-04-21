# Cheetah API

Lastests data model for API

## User control

User can sign up to ask for an api key

- User
    - pk (uuid)
    - django default user

- UserKey
    - Date created
    - Expiration date
    - Monthly max requests
    - Daily max requests
    - Key status (non-active, daily, monthly, unlimited)

## Dota 2 Heroes


- Dota2 Heroes
    - id (connected to valve's)
    - name (connected to valve's )
    - localized name (connected to valve's)
    - nicknames (all the ways a hero can be called)
    - Custom image

- Dota Items
    - id (connected to valve's)
    - name (connected to valve's )
    - localized name (connected to valve's)
    - nicknames (all the ways a hero can be called)
    - Is recipe
    - Cost
    - Custom image

- Dota commands
    - Name
    - Description
    - Category
    - Chat command
    - Console command
    - Arguments
    - Default arguments

- Dota command categories
    - Name
    - Image
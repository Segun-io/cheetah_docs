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

## Heroes

- Hero
    - id (connected to valve's)
    - name (connected to valve's )
    - localized name (connected to valve's)
    - nicknames (all the ways a hero can be called)
    - Custom image

## Items

- Item
    - id (connected to valve's)
    - name (connected to valve's )
    - localized name (connected to valve's)
    - nicknames (all the ways a hero can be called)
    - Is recipe
    - Cost
    - Custom image
    
## Commands

- Command
    - Name
    - Description
    - Category
    - Chat command
    - Console command
    - Arguments
    - Default arguments

- Command Category
    - Name
    - Image
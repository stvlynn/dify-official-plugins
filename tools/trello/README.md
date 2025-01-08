# Overview
Trello is a popular project management and collaboration tool. This plugin includes a variety of tools that allow users to manage boards, lists, and cards programmatically within workflows. By using the Trello Plugin, you can automate tasks such as creating boards, updating cards, fetching board details, and enhancing productivity and streamlining project management processes.

# Configure
1. Prerequisites
Before using the Trello Plugin:
1. Register a Trello account at [Trello](https://trello.com/).
2. Obtain your Trello API Key and **API Token**:
  - Visit the [Trello API Introduction](https://developer.atlassian.com/cloud/trello/guides/rest-api/api-introduction/).
  - Generate your API Key and Token by following the instructions provided.

2. Install and Authorize the Plugin
1. Go to the Dify Marketplace and install the **Trello Plugin**.
![](./_assets/trello_install.PNG)
2. Add any of the Trello tools (e.g., "Create Board" or "Get Board by ID") to your workflow.
3. Click on the "To authorize" button in the tool configuration panel.
4. Enter your Trello API Key and API Token in the respective fields.
5. Save your credentials to complete the authorization process.

3. Tools Included in the Plugin
The Trello Plugin includes the following tools:

Board Management
- **Create Board**: Create a new Trello board.
- **Fetch All Boards**: Retrieve all boards associated with your account.
- **Get Board by ID**: Fetch details of a specific board using its ID.
- **Update Board by ID**: Update properties of an existing board.
- **Delete Board**: Delete a specified board.

List Management
- **Create List on Board**: Add a new list to an existing board.
- **Get Lists from Board**: Retrieve all lists from a specified board.

Card Management
- **Create New Card on Board**: Add a new card to a specific list on a board.
- **Get Board Cards**: Retrieve all cards from a specified board.
- **Get Filtered Board Cards**: Fetch cards that meet specific filter criteria.
- **Update Card by ID**: Update details of an existing card using its ID.
- **Delete Card by ID**: Delete a specific card using its ID.

Action Retrieval
- **Get Board Actions**: Fetch actions performed on a specific board for activity tracking.
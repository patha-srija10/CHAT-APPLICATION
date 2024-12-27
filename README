# CHAT-APPLICATION
# Chat Application: README

## Overview
This is a Python-based console application that simulates a chat system with features like group chats, personal chats, user roles (admin and members), and message management.

## Features
1. *User Management*
   - Two user roles: Admin and Member.
   - Admins have additional privileges such as deleting any message, adding/removing users from chats, and viewing chat history.
   - Members can send and delete their own messages.

2. *Chat Management*
   - Create group chats with multiple participants.
   - Create personal (one-on-one) chats.
   - Send, receive, and delete messages.
   - View chat history.

3. *Admin Privileges*
   - Kick users from a chat.
   - Promote members to admin.
   - Add or remove users from a group chat.
   - Delete any message in a chat.

4. *Message Management*
   - Edit messages.
   - Delete own messages.
   - Broadcast messages to all participants except the sender.

## Class Descriptions
### 1. User
- *Attributes*:
  - username: The username of the user.
  - role: Role of the user ("admin" or "member").
- *Methods*:
  - send_message: Sends a message to a chat.
  - receive_message: Receives a message in the chat.
  - delete_own_message: Deletes a message sent by the user.

### 2. Admin (inherits from User)
- *Additional Attributes*:
  - privileges: List of privileges available to the admin.
- *Additional Methods*:
  - delete_message: Deletes any message in a chat.
  - kick_user: Removes a user from a chat.
  - promote_user: Promotes a member to admin.
  - add_user_to_chat: Adds a user to a group chat.
  - remove_user_from_chat: Removes a user from a group chat.
  - view_chat_history: Views the entire chat history.

### 3. Member (inherits from User)
- A simpler version of User with no additional methods.

### 4. Message
- *Attributes*:
  - sender: The user who sent the message.
  - content: The text of the message.
  - timestamp: Time the message was sent.
- *Methods*:
  - edit_message: Edits the content of the message.

### 5. Chat
- *Attributes*:
  - chat_id: Unique identifier for the chat (e.g., group name or personal chat identifier).
  - participants: List of users in the chat.
  - messages: List of messages in the chat.
- *Methods*:
  - add_message: Adds a new message to the chat.
  - broadcast_message: Sends the message to all participants except the sender.
  - remove_message: Removes a message from the chat.
  - view_chat_history: Returns all messages in the chat.

### 6. ChatRoom
- *Attributes*:
  - chats: List of all chats (group and personal).
- *Methods*:
  - create_group_chat: Creates a new group chat.
  - create_personal_chat: Creates a one-on-one chat.
  - get_chat: Fetches a chat by its ID.
  - list_chats: Lists all chat IDs.

## How to Run
1. Ensure you have Python installed (version 3.6 or higher).
2. Copy the code into a Python file, e.g., chat_application.py.
3. Run the script using:
   
   python chat_application.py
   
4. Follow the prompts in the console to interact with the application.

## Usage
### Main Menu Options
1. *Create a Group Chat*:
   - Enter a group chat name and participant usernames (comma-separated).

2. *Join a Chat*:
   - View available chats and select one to join.

3. *Send Message to Group Chat*:
   - Enter your username, select a chat, and type your message.

4. *Send Message to Personal Chat*:
   - Specify the sender and recipient usernames.
   - Create a personal chat if it does not exist.

5. *View Chat History*:
   - Choose to view group or personal chat history.

6. *Delete Your Own Message*:
   - View messages you have sent and delete them.

7. *Admin: Delete Any Message*:
   - Admins can view and delete any message in a chat.

8. *Add User to Group Chat (Admin Only)*:
   - Admins can add new or existing users to a group chat.

9. *Remove User from Group Chat (Admin Only)*:
   - Admins can remove participants from a group chat.

10. *Exit*:
    - Ends the application.

## Example Scenario
1. Admin Thrisha creates a group chat with members Meghana and Srija.
2. Members send messages to the group.
3. Admin views the chat history and deletes an inappropriate message.
4. Admin adds a new member Chandu to the chat.
5. Member Meghana decides to delete her own message.

## Notes
- Usernames must be unique.
- Admin privileges are limited to group chats and do not apply to personal chats.
- Messages are timestamped using the current system time.

## Future Improvements
- Implement authentication for users.
- Add a graphical user interface (GUI).
- Support file sharing and multimedia messages.
- Enable notifications for new messages.

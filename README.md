# Lab-04: User Stories

- Name: Bastián Cepeda
- Major: Computer Science

## Application Overview
The messaging app allows registered users to send and receive messages without requesting friend requests. Users can access their ongoing chats, view detailed message threads, and initiate one-on-one conversations. The app solely focuses on the basic functionalities of sending and receiving texts, which means users are unable to edit or delete messages.

## User Stories

### 1. Viewing All Registered Users
**As a** registered user, **I want to** see a scrollable list of all users, **so that** i can choose who to message.

**Acceptance Criteria:**

- List displays usernames and profile pictures

- Alphabetical sorting with search functionality

- Online users have status indicator

### 2. Accessing My Chat List
**As a** frequent user, **I want to** see my active conversations, **so that** i can quickly resume chats.

**Acceptance Criteria:**
- Chats ordered by most recent activity
- Unread messages have visual badge (counter)
- Each chat shows: last message preview + timestamp

### 3. Starting a New Conversation
**As a** new user, **I want to** tap any user to start messaging, **so that** i can communicate without approvals.

**Acceptance Criteria:**
- Empty message view opens when selecting new user
- Keyboard automatically focuses on text input
- First sent message creates new chat in list

### 4. Sending a Text Message
**As a** sender, **I want to** type and send messages, **so that** the recipient can read them.


**Acceptance Criteria:**
- Message appears immediately after sending
- Timestamp shows "HH:MM" format
- Input field clears after sending

### 5. Viewing a Message Thread
**As a** participant, **I want to** scroll through conversation history, **so that** i can reference past messages.

**Acceptance Criteria:**
- Messages display sender avatar + name
- Distinct visual style for sent vs received
- Auto-scrolls to newest message on open

### 6. Receiving Real-Time Message Notifications
**As a** recipient, **I want to** get alerts for new messages, **so that** i don't miss conversations.

**Acceptance Criteria:**
- Push notification appears for new messages
- Chat list updates message preview instantly
- Unread counter increments in real-time

### 7. Ensuring Message Delivery
**As a** concerned sender, **I want to** see message status, **so that** i know it was delivered.

**Acceptance Criteria:**
- "Delivered" status appears under sent messages
- Network errors show retry option
- Timestamp updates when message is received

### 8. Checking User Availability

**As a** considerate communicator, **I want to** see last active time, **so that**  i know when to expect replies.

**Acceptance Criteria:**
- "Last seen: X min ago" in user profiles
- Different statuses (Online/Offline)
- Updates in real-time

### 9. Managing Message Notifications
**As a** privacy-conscious user, **I want to** customize notification settings per conversation, **so that** I can control which chats alert me.

**Acceptance Criteria:**

- Mute/unmute toggle in chat settings

- Custom notification sounds per chat

- Visual indicator for muted conversations

### 10. Searching Message History
**As a** user with long conversations, **I want to** search within message threads, **so that** I can find specific information quickly.

**Acceptance Criteria:**

- Search bar in conversation view

- Highlights found terms in messages

- Shows timestamps of found messages

### 11. Sharing Media in Conversations

**As a** creative communicator, **I want to** share images in messages, **so that** I can enhance my conversations.

**Acceptance Criteria:**

- Attachment button in message composer

- Preview of sent/received images

- Storage optimization for media files

### 12. Blocking Unwanted Users
**As a** user concerned about harassment, **I want to** block other users, **so that** I can prevent unwanted communication.

**Acceptance Criteria:**

- Block option in user profile menu

- Immediate cessation of messages from blocked users

- Visual indication of blocked status

### 13. Syncing Across Devices
**As a** multi-device user, **I want to** have my messages synced across all my devices, **so that** I can continue conversations seamlessly.

**Acceptance Criteria:**

- Real-time sync between mobile and web

- Read status consistent across devices

- Notification dismissal syncs everywhere

### 14. Viewing Message Read Status
**As a** curious sender, **I want to** see when my messages are read, **so that** I know if they've been seen.

**Acceptance Criteria:**

- "Read" status indicator under messages

- Timestamp of when message was read

- Option to disable read receipts in settings

### 15. Archiving Old Conversations
**As a** organized user, **I want to** archive inactive chats, **so that** I can declutter my chat list without deleting history.

**Acceptance Criteria:**

- Archive button in chat options

- Archived chats accessible in separate view

- Chats unarchive when new messages arrive

### 16. Setting a Custom Status
**As a** expressive user, **I want to** set a custom status message, **so that** others can know my availability or mood.

**Acceptance Criteria:**

- Status editor in profile settings

- Status visible to others in user list

- Predefined status options available

### 17. Scheduling the sending of a message
**As a** busy user, **I want to** schedule a message to be sent at specific times, **so that** I can communicate efficiently across different time zones or during optimal hours.

**Acceptance Criteria:**
- Option to set delivery time when composing

- Visual distinction between scheduled/sent messages

- Confirmation when scheduled message is sent

### 18. A user wants to send an SOS message
**As a** user in potentially unsafe situations, **I want to** trigger an emergency alert with one gesture, **so that** my trusted contacts receive my location and chat context immediately.

**Acceptance Criteria:**
- Sends live location GPS
- Activates silent mode automatically
- Confirms alert delivery to sender


### 19. Activates focus mode to mute notifications
**As a** user needing deep work periods, **I want to** mute all non-critical notifications, **so that** I avoid distractions while staying reachable for emergencies.

**Acceptance Criteria:**
- Auto-responder for muted chats
- Visual "In Focus Mode" status in chats
- Scheduled activation


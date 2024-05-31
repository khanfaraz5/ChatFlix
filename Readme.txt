First we made splash screen, we created a new activity for this and designed it. I moved intent filters in android manifest inside the splash screen activity 

Next, design all the UIs for all 3 login activities.

Write code for LoginPhoneNumberActivity, then LoginOtpActivity

After that , connect to firebase.

Complete OTP sending part in LoginOtpActivity.

Complete resend OTP part in LoginOtpActivity.

Write code for getting UserId from firebase in FirebaseUtil.java

Set the user name for user and store that in the database of firebase to log in the user using that name in LoginUserNameActivity

After that write code for already logged in condition in FirebaseUtil and call it inside splash activity.

Design the MainActivity.

Design the chat and profile fragments.

Design the SearchUserActivity.

Design the RecentChatRecyclerAdapter for displaying recent chats.

Implement the profile section in ProfileFragent, add logout , update features.

Implement the profile picture feature in ProfileFragment.

Add features where updated profile pic seen in recent chats and chat activity.

Implement push notifications




code SearchUserActivity.

Design the SearchUserRecyclerAdapter, inherit that inside SearchUserActivity.

Implement ChatActivity.

Add methods in AndroidUtil so that real name is shown of user in ChatActivity instead of "UserName" written there.

Implement ChatRoomModel.

Create chatRoom Function in ChatActivity and also implement its methods in FirebaseUtil.

Impement the send message function in ChatActivity.

Write code for ChatMessageModel.java which will handle all the necessary variables for chat.

Design the chat recycler view.

Design Chat recycler adapter class.

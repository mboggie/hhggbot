The Hitchhikers' Guide to the Galaxy Twitter Bot
@hhggbot
Version 0.0

Components:
- Twitter Streaming API for listening for new messages
- Frotz (http://sourceforge.net/projects/frotz/) for processing original story file
- MySQL for server storage of game state, keyed from @username
- (More important for later) Inform 7 tool for creating new interactive fiction files

Todos: 
How much game state must Frotz be fed, to understand where the user is? 
|__More to the point - how does Frotz store game states? Are multiple instances required??

What is simplest way to create custom templated pages for long reponses / images / eastereggs?
|__Should we cache / reuse long response pages, or generate per user?

Can we pass messages into / out of Frtoz via something other than C? (God I hope so...)

Register hhggbot.com when appropriate / ready
 
Dependencies Installed: twitstream 0.1, tlslite (to support twitstream)

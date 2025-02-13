# Server settings    

Server settings can only be changed by admins, users with the 'Ban Members' permission or .fmbot admins.

### .serverreactions

Sets the emote reactions for every .fm command in your server.

To disable, simply use `.serverreactions` without any emotes.

Make sure the emotes you enable are on your server.

Max amount of emotes is 3. Please put a space between every emote.

!!! note "Examples"
    `.serverreactions :PagChomp: :PensiveBlob:`

    `.serverreactions 😀 😯 🥵`

    `.serverreactions 😀 😯 :PensiveBlob:`

    `.serverreactions`

---   
### .togglecommand

You can enable/disable commands per channel.

To view all disabled commands, use `.togglecommand` without any options.

Make sure to enter commands without without the `.` prefix.

You can toggle all commands at once by using the `all` option.

!!! note "Examples"
    `.togglecommand`

    `.togglecommand chart`

    `.togglecommand whoknows chart taste`

    `.togglecommand all`

---        
### .toggleservercommand

You can enable/disable commands server-wide.

To view all disabled commands, use `.toggleservercommand` without any options.

Make sure to enter commands without without the `.` prefix.

!!! note "Examples"
    `.toggleservercommand`

    `.toggleservercommand chart`

    `.toggleservercommand whoknows`

---   

### .prefix

This command allows you to change the .fmbot prefix on your server.

To disable your custom prefix, use the `prefix` command without any prefix behind it. 

Note that you can always mention the bot, this will work regardless of prefix.

!!! note "Examples"
    `.prefix`

    `.prefix !`

    `@.fmbot prefix`

    
!!! note "Examples of commands when prefix is set to !"
    `!fm`

    `!chart`

    `!whoknows`
    
    `!topalbums`
    
    `!prefix`
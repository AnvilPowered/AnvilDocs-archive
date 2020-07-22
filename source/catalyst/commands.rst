========================
Commands and Permissions
========================

.. note::

    This page is currently under development and is subject to be changed. If you notice any issues with this page please report them.

This page provides a list of available commands and their permissions

+-----------+------------------------+-------------------------------------------+----------------------------------------+
| Command   | Alias                  | Permission                                | Usage                                  |
+===========+========================+===========================================+========================================+
| ban       | cancban                | catalyst.command.ban                      | /ban <player> [reason]                 |
+-----------+------------------------+-------------------------------------------+----------------------------------------+
| tempban   | ctempban               | catalyst.command.tempban                  | /tempban <player> <duration> [reason]  |
+-----------+------------------------+-------------------------------------------+----------------------------------------+
| broadcast | cbroadcast             | catalyst.command.broadcast                | /broadcast <message>                   |
+-----------+------------------------+-------------------------------------------+----------------------------------------+
| find      | cfind                  | catalyst.command.find                     | /find <player>                         |
+-----------+------------------------+-------------------------------------------+----------------------------------------+
| info      | cinfo                  | catalyst.command.info                     | /info <player>                         |
+-----------+------------------------+-------------------------------------------+----------------------------------------+
| kick      | ckick                  | catalyst.command.kick,                    | /kick <player> [reason]                |
|           |                        |  catalyst.command.kick.exempt             |                                        |
+-----------+------------------------+-------------------------------------------+----------------------------------------+
| list      | clist                  | catalyst.command.list                     | /list                                  |
+-----------+------------------------+-------------------------------------------+----------------------------------------+
| message   | msg, pm, whisper, m, t | catalyst.command.message                  | /msg <player> <message>                |
+-----------+------------------------+-------------------------------------------+----------------------------------------+
| mute      | cmute                  | catalyst.command.mute                     | /mute <player> [reason]                |
+-----------+------------------------+-------------------------------------------+----------------------------------------+
| nick      | cnick, nickname        | catalyst.command.nickname,                | /nick <nickname>                       |
|           |                        | catalyst.command.nickname.color,          | /nick other <player> <nickname>        |
|           |                        | catalyst.command.nickname.other           |                                        |
+-----------+------------------------+-------------------------------------------+----------------------------------------+
| send      | csend                  | catalyst.command.send                     | /send <player> <server>                |
+-----------+------------------------+-------------------------------------------+----------------------------------------+
| socialspy |                        | catalyst.command.socialspy,               | /socialspy                             |
|           |                        | catalyst.command.socialspy.onjoin         |                                        |
+-----------+------------------------+-------------------------------------------+----------------------------------------+
| stafflist |                        | Base: catalyst.command.stafflist.base,    |                                        |
|           |                        | Owner: catalyst.command.stafflist.owner,  |                                        |
|           |                        | Admin: catalyst.command.stafflist.admin,  |                                        |
|           |                        | Staff: catalyst.command.stafflist.staff,  |                                        |
+-----------+------------------------+-------------------------------------------+----------------------------------------+
| tempmute  | ctempmute              | catalyst.command.mute                     | /tempmute <player> <duration> [reason] |
+-----------+------------------------+-------------------------------------------+----------------------------------------+
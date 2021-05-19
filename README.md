# ansible-role-systemd

This role exists primarily to provide the  "reload systemd" handler,
which can be used in other roles to trigger a `systemctl daemon
reload` when modifying unit files.

# none-injectable sql function
this is a php function that accepts raw sql string with variables without being sql injectable.


limitations:

can't use $ in sql for anything except variables.

doesn't force single qoutes. which prevents the sql injection.

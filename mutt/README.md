mutt patched with pgp_verbose_mime patch

http://dev.mutt.org/trac/ticket/3478

Allows signature file to be renamed from "noname" to something more meaningful.

In muttrc:
pgp_mime_signature_filename="<name you want to give to your signature>" 
set pgp_mime_signature_description="<description you want to give to your signature>" 

FROM openproject/community:6
LABEL org.freenas.interactive="true"				\
      org.freenas.version=“6.1.0” 				\
      org.freenas.expose-ports-at-host="true" 			\
      org.freenas.autostart="true" 				\
      org.freenas.bridged="true" 				\
      org.freenas.web-ui-protocol="http" 			\
      org.freenas.port-mappings=“80:8080/tcp" 			\
      org.freenas.volumes="[					\
          {							\
              \"name\": \"/var/lib/postgresql/9.4/main\",	\
              \"descr\": \”pgdata\”				\
          },							\
          {							\
              \"name\": \"/var/log/supervisor\",		\
              \"descr\": \”logs\”				\
          },							\
          {							\
              \"name\": \"/var/db/openproject\",		\
              \"descr\": \”static\”				\
          }							\
      ]” 							\
      org.freenas.settings="[ 					\
          {							\
              \"env\": \”SECRET_KEY_BASE\”,			\
              \"descr\": \”Secret key\”,			\
              \"optional\": false				\
          }							\
	]”

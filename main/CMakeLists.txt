set(COMPONENT_SRCS "main.c". 
                   "wifi.c")
set(COMPONENT_ADD_INCLUDEDIRS ".")
# Embed the server root certificate into the final binary
set(COMPONENT_EMBED_TXTFILES ${project_dir}/server_certs/ca_cert.pem)

register_component()

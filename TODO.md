rename to tenant-control-panel
user authentication (login, register)

api:
istcp should work on bare metal: 
http://<nodeId>.tcp.metal.<domain>.com/api/users/<user>
http://<nodeId>.tcp.metal.<domain>.com/api/namespaces/<namespace>

ui:
form: <domain>.com/auth/register
form: <domain>.com/auth/login
list: <domain>.com/tenants
view: <domain>.com/<user>/<namespace>
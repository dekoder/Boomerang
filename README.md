# Boomerang ![GitHub All Releases](https://img.shields.io/github/downloads/paranoidninja/Boomerang/total)
Boomerang is a tool to expose multiple internal servers to web/cloud using HTTP+TCP Tunneling. The Server will expose 2 ports on the Cloud. One will be where tools like proxychains can connect over socks, another will be for the agent to connect. The agent can be executed on any internal host. The agent will connect to the server and listen for any connection that can be forwarded to internal machine like a socks server. A more detailed information can be found in the image below. Features like authentication are in pipeline and will be added soon. <br/>
Agent & Server are pretty stable and can be used in Red Team for Multiple levels of Pivoting and exposing services to external/other networks<br/><br/>

![Alt text](docs/Boomerang_v0.1.png?raw=true "Boomerang")

<br/>
Boomerang Agent & Server support Windows, Linux and Arm architecture <br/>
Features in Progress:
Proxy Authentication (Use IP Whitelisting for C2s till then)

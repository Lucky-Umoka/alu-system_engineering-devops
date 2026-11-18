# load_balancer

Scripts that add a custom response header to nginx and install an HAProxy load balancer.

- 0-custom_http_response_header: adds the X-Served-By header with the server hostname
- 1-install_load_balancer: installs HAProxy and balances traffic between web-01 and web-02

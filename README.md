# PA State Park MCP Service

This MCP service will provide information about PA State parks based on distance from a location.


### gpsLogger
copy mcpPAStateParks.service to /etc/systemd/system

- sudo systemctl daemon-reload          # Reload systemd to recognize the new service file
- sudo systemctl enable mcpPAStateParks.service  # Enable the service to start on boot
- sudo systemctl start mcpPAStateParks.service

- sudo systemctl status mcpPAStateParks.service


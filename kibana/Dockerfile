# https://github.com/elastic/kibana-docker
FROM docker.elastic.co/kibana/kibana:6.3.0

# Add your kibana plugins setup here
# Example: RUN kibana-plugin install <name|url>
RUN /usr/share/kibana/bin/kibana-plugin install https://github.com/sivasamyk/logtrail/releases/download/v0.1.27/logtrail-6.3.0-0.1.27.zip

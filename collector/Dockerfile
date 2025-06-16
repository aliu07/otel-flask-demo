# Use the official OpenTelemetry Collector image
FROM otel/opentelemetry-collector:latest

# Copy the OpenTelemetry Collector configuration file
COPY otel-collector-config.yaml /etc/otel-collector-config.yaml

# Run the collector with the custom configuration
CMD ["--config=/etc/otel-collector-config.yaml"]

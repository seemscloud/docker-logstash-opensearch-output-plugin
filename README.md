# Logstash with Opensearch Output Plugin

## Send event
```bash
curl -X PUT http://logstash:8080 \
    -H "Content-Type: application/json" \
    -d '{"message":"example message"}'
```
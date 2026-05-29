# Performance Testing

Framework uses Apache JMeter.

## Location

jmeter/

Contains:

Test Plans (.jmx)

CSV Data

Reports

---

## Run JMeter Test

jmeter -n \
-t jmeter/opencart_load.jmx \
-l reports/result.jtl

---

## Generate HTML Report

jmeter -g reports/result.jtl \
-o reports/html

---

## Sample Metrics

Response Time

TPS

Error %

Latency

Throughput

95th Percentile

99th Percentile

---

## Performance Pipeline

JMeter
↓
Result File
↓
HTML Report
↓
CI/CD Publish

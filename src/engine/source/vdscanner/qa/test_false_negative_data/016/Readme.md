# Description

Vulnerability detection validation for **_openssl_** package.

# Platforms

## Ubuntu Jammy

- Input events
  - [001](input_001.json)

| Name      | Version           | Feed      | CVE IDs       | Expected      |
|-----------|-------------------|-----------|---------------|---------------|
| openssl   | 3.0.2-0ubuntu1.15 | Canonical | CVE-2014-0160 |Not vulnerable |
| openssl   | 1.0.1             | NVD       | CVE-2014-0160 |Vulnerable     |
| openssl   | 1.0.1g            | NVD       | CVE-2014-0160 |Not vulnerable |
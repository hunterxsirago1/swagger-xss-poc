# Swagger UI XSS Proof of Concept (PoC)

This repository contains maliciously crafted YAML definitions designed to demonstrate a Cross-Site Scripting (XSS) vulnerability within specific versions of Swagger UI. 

### Contents
- `abcd.json` / `efgh.json`: Metadata configuration pointing to the poisoned YAML.
- `test(1).yaml`: The swagger file containing the XSS payload hidden inside the `description` field utilizing `<math>` and `<svg>` tags.

### Disclaimer
This repository is strictly for educational purposes and responsible vulnerability disclosure. Do not use these payloads against systems you do not have explicit permission to test.

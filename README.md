# vscan-anti-csrf-token-checker
Analyzes HTML forms to determine if anti-CSRF tokens are present and correctly implemented, identifying potential CSRF vulnerabilities. - Focused on Lightweight web application vulnerability scanning focused on identifying common misconfigurations and publicly known vulnerabilities

## Install
`git clone https://github.com/ShadowGuardAI/vscan-anti-csrf-token-checker`

## Usage
`./vscan-anti-csrf-token-checker [params]`

## Parameters
- `-h`: Show help message and exit
- `--verbose`: No description provided

## License
Copyright (c) ShadowGuardAI

## Notes
- If the page cannot be fetched, the tool prints a fetch failure line and exits 1: a failed fetch is not a finding of no forms. A fetched page with no forms prints "No forms found on the page." and exits 0.

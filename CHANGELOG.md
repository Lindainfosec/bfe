<!--
This changelog should always be read on `master` branch. Its contents on other branches
does not necessarily reflect the changes.
-->

# Changelog

## v0.2.0 (unreleased)

### Added
- Add proxy protocol to be compatible with F5 BigIP/Citrix ADC etc
- Add mod_access to write request/session log in customized format
- Add mod_key_log to wirte tls key log so that external programs(eg. wireshark) can decrypt TLS connections for trouble shooting
- Add security grade 'A+' in tls
- Add condition primitive: req_query_value_contain/req_header_value_contain/req_cookie_value_contain
- Documents optimization

### Changed
- reverseproxy: flush response header immediately if flushInterval<0


## v0.1.0

### Core Features
- Multiple protocols supported, including HTTP, HTTPS, SPDY, HTTP2, WebSocket, TLS, etc
- Content based routing, support user-defined routing rule in advanced domain-specific language
- Support multiple load balancing policies
- Flexible plugin framework to extend functionality. Based on the framework, developer can add new features rapidly
- Detailed built-in metrics available for service status monitor

# ghichep-haproxy
Ghi chép về haproxy

# Mục lục

A. Các tổng quan

- [1. HA Proxy - High Availability Proxy](docs/ha-overview.md)
	- [1.1 Mục đích sử dụng của HA Proxy](docs/ha-overview.md#about)
	- [1.2 Cài đặt HA Proxy](docs/ha-overview.md#install)
	- [1.3 Tổng quan về cấu trúc file cấu hình của HA Proxy](docs/ha-overview.md#instruc)

- [2. Tổng quan về Keep Alived](docs/ka-overview.md)
	- [2.1 Vấn đề hướng tới của Keep Alived](docs/ka-overview.md#issue)
	- [2.2 Mô hình sơ khai của một hệ thống sử dụng KeepAlived](docs/ka-overview.md#models)
	- [2.3 Cài đặt KeepAlived](docs/ka-overview.md#install)
	- [2.4 Cấu hình kết hợp với HA Proxy để kiểm tra kết quả](docs/ka-overview.md#config)

- [3. Cơ bản về các dòng cấu hình trong file cấu hình của KeepAlived](docs/ka-configure-introduce.md)
	- [3.1 Các block cấu hình trong keepalived](docs/ka-configure-introduce.md#about)
	- [3.2 Nội dung cấu hình trong block `global_defs`](docs/ka-configure-introduce.md#global_defs)
	- [3.3 Nội dung cấu hình trong block `static_ipaddress static_routes`](docs/ka-configure-introduce.md#static_ipaddress)
	- [3.4 Nội dung cấu hình trong block `vrrp_instance` (đang hoàn thiện)](docs/ka-configure-introduce.md#vrrp_instance)
### Object: FirstEmployee

## Attributes:
- name: "Joe Bob"
- job_title: "Server"
- is_hourly: false
- hours_worked: [5,8,4,6,7]
- rate: 8.5

## Methods:
- change_job_title: job_title = "Cook"
- change_hourly: is_hourly = true
- change_name: "Joe Smith"
- add_hours_worked: hours_worked << 4
- calculate_pay_check: if hourly then `hours_worked.sum * rate` else do nothing

# Visit https://docs.rilldata.com/reference/project-files to lea
title: "Customer Unit Economics Dashboard"
model: "metrics_margin_model"
default_time_range: "P4W"
smallest_time_grain: "day"
timeseries: "__time"
measures:
 - label: "Total Cost"
 expression: "SUM(cost)"
 name: measure
 description: "The sum of cost"
 format_preset: currency_usd
 - label: "Total Revenue"
 expression: SUM(revenue)
 name: total_records
 description: The sum of revenue
# Visit https://docs.rilldata.com/reference/project-files to lea
title: "Customer Unit Economics Dashboard"
model: "metrics_margin_model"
default_time_range: "P4W"
smallest_time_grain: "day"
timeseries: "__time"
measures:
 - label: "Total Cost"
 expression: "SUM(cost)"
 name: measure
 description: "The sum of cost"
 format_preset: currency_usd
 - label: "Total Revenue"
 expression: SUM(revenue)
 name: total_records
 description: The sum of revenue
property: "pipeline"
 description: "The pipeline incurring costs"
 - label: "Cost by Environment"
 property: "environment"
 description: "The environment incurring costs"
available_time_zones:
 - America/Los_Angeles
 - America/Chicago
 - America/New_York
 - Europe/London
 - Europe/Paris
 - Asia/Jerusalem
 - Europe/Moscow
 - Asia/Kolkata
 - Asia/Shanghai
 - Asia/Tokyo
 - Australia/Sydney

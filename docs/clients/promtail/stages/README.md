# Stages

This section is a collection of all stages Promtail supports in a
[Pipeline](../ppipelines.md).

Parsing stages:

  * [regex](./regex.md): Extract data using a regular expression.
  * [json](./json.md): Extract data by parsing the log line as JSON.

Transform stages:

  * [template](./template.md): Use Go templates to modify extracted data.

Action stages:

  * [timestamp](./timestamp.md): Set the timestamp value for the log entry.
  * [output](./output.md): Set the log line text.
  * [labels](./labels.md): Update the label set for the log entry.
  * [metrics](./metrics.md): Calculate metrics based on extracted data.

Filtering stages:

  * [match](./match.md): Conditionally run stages based on the label set.


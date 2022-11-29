# Concourse Flight Plans

[Concourse](https://concourse-ci.org/) is an extremely capable automation utility, enabling continuous integration, delivery, task automation, and much much more.

There are typically two paths to building Concourse pipelines:

1. Bespoke build a pipeline from scratch, adding features over time
2. Deploy a template and adapt the source to fit

The first allows the pipeline to grow organically with the project, but often means developers (or DevOps teams) need to rewrite the wheel several times. Often with minor variations and errors.

The second brings consistency and established patterns, but not every project neatly fits those patterns.

Some middle ground is needed. That's where Flight Plans comes in: Concourse pipeline templates that set established patterns while still maintaining customizablility.

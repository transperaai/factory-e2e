# factory-e2e

Sample project for the factory's automated end-to-end test (F-01, `transperaai/Software-factory` `docs/f-01-plan.md`, decision D3).

All data here is made up: Acme Logistics and everyone in it are invented. Each run of `f01-e2e.yml` in Software-factory resets `main` to the `e2e-seed` tag, then drives steps 1 to 8: a transcript goes through intake, claim confirmation, the BA agent and approval.

Don't put real client data here, and don't build on `main`: it is reset on every run.

# Changelog
All notable changes to the Tufts FastQC Open OnDemand app are documented in
this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).
This app has no tagged releases yet, so entries are grouped by date.

## [Unreleased]
### Changed
- Rewrote `README.md` and `CHANGELOG.md` for FastQC (replacing the OSC MATLAB
  template text).

## 2026-07-17
### Changed
- Start-of-session email is now opt-in via the `bc_email_on_started`
  checkbox; removed the always-on start/end emails from `submit.yml.erb`.
- Request cores with `--cpus-per-task` instead of `--ntasks`.

## 2026-07-16
### Changed
- Made the `ta_qos` ("Request priority start") option consistent with the
  other Tufts apps: submits with `--qos=interactive` when checked, and
  `form.js` caps the form to the interactive QOS limits.

## 2026-07-14
### Changed
- Switched to the shared resource discovery partial for the partition, core,
  memory, and walltime fields.
- Reorganized widget order in the launch form.

## 2026-02-05
### Changed
- Updated the desktop session to the new XFCE setup.
- Changed the app subcategory to Bioinformatics.

## 2025-08-28
### Added
- Initial deployment of the FastQC app (FastQC 0.12.1) for the noVNC test.

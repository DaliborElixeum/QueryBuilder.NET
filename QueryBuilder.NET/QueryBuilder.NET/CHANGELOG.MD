# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [UNRELEASED]

### Added
- custom naming of identity column for inserts

### Fixed
- returning columns in inserts are enclosed in quotes as they should be 

## [0.3.1]

### Changed
- Insert now recognizes navigation property and ignores it automatically, without need of `NotMappedAttribute`. This is important when combined with EntityFramework

## [0.3.0]

### Changed
- main namespace to `QueryBuilderDotNet` to avoid conflict with `Microsoft.AspNetCore.Http.Extensions.QueryBuilder`

## [0.2.3]

### Changed
- first public package release
# Test Case: UV Wildcard Format

## Package Manager
UV

## Python Version Detection
- **Source**: pyproject.toml (requires-python)
- **Expected Version**: 3.11.*
- **Format**: Wildcard (any 3.11.x version)

## Files Present
- pyproject.toml - requires-python = "3.11.*"
- uv.lock

## Test Purpose
Test UV's handling of wildcard version specifications (3.11.* means any patch version of 3.11).

# api

This package defines all api functionality in the form of interfaces. packages that implement this api should use the db package in their function signatures when making database calls and use a mocked implementation of db package in tests.
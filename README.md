# Adapter Pattern: School Management Systems

This example integrates systems with different native APIs into one common
`SchoolManagementApp` interface:

- `AttendanceSystemAdapter` delegates `integrateSystem()` to `markAttendance()`.
- `GradingSystemAdapter` delegates `integrateSystem()` to `recordGrades()`.
- `LibrarySystemAdapter` delegates `integrateSystem()` to `manageBooks()`.

Compile the adapter classes with:

```bash
javac *.java
```
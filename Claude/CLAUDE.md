# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a .NET solution (Claude.sln) using Visual Studio solution format. The solution is currently empty with no projects added. IDE configuration is present for JetBrains Rider.

## Build Commands

```bash
dotnet build Claude.sln              # Build the solution
dotnet build Claude.sln -c Release   # Build in Release mode
dotnet test                           # Run all tests
dotnet run --project <ProjectName>    # Run a specific project
```

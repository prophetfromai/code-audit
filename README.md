# Code Audit

A tool that analyses git history against work requests so business owners can verify whether outsourced development work was actually done.

## The Problem

When you hire a freelance developer (Fiverr, Upwork, etc), you often can't tell whether the work was actually done properly. You're paying for time or deliverables but have no easy way to verify what happened in the codebase against what was requested.

## What It Does

Point it at a git repo and a work brief (tickets, task descriptions, requirements), and it analyses the git history — commits, diffs, timing, file changes — against what was asked for. The output is a clear report for the business owner: was the work done? Was it done well? Does the activity match the claimed effort?

# Interface gráfica simples para Login

Meu primeiro projeto simples e apenas demonstrativo. Login de único fator.

>Status: debugging 🐌<br>
>Version: not applicable<br>
>Date released: 11/18/2025

## What does it do? - Purpose
Opens a window as a gatekeeper what only allows access when both username and password are correct.

## Content
Single form without dependencies.
Two textbox, one button and one passive label.

## How does it work? - Behavior
The button "Connect" is configured to negate access when:
* Both username and password are `null` or empty;
* Username or password is `null` or empty;
* Both are incorrect;
* Username or password is incorrect.

When is allowed to access:
* "Disconnected" (red) label turns in "Connected" (green).

## What was used? - Resources
GUI          | .NET  | SQL | Web
------------ | ----- | --- | ---
Windows Forms| v.8.0 | No  | No

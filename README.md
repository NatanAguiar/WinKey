# WinKey

@echo off
echo ATENÇÃO: Este script executará um comando remoto do PowerShell
echo.
echo Comando que será executado:
echo irm https://get.activated.win | iex
echo.
pause

PowerShell -NoProfile -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://get.activated.win | Invoke-Expression"
pause

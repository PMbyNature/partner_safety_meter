When localStorage is cleared, the script is not correctly checking that no reset has happened, so it defaults to 0 instead of calculating from March 3, 2025.
The script needs to always calculate from March 3, 2025, unless a reset was explicitly performed.

# Problems and questions

| Problem | What to try |
| :------ | :---------- |
| The page looks old, or a new feature is missing | Hard refresh (Ctrl+Shift+R on Windows). The header shows the display and server versions. |
| "No data on remote" | The server is not answering. Try again in a minute, and tell the Gander Oceanic team if it stays. |
| Track, transfer, SELCAL or contact me does nothing | Check that you are signed in with a position, EuroScope is connected as that position, and the plugin is loaded. The result is shown at the bottom of the aircraft menu. |
| Send buttons only copy | `autotype=1` is missing from `vnaaats.cfg`, or Windows refused to let the plugin type. Use the Copy buttons and paste into EuroScope. |
| A flight is missing | It may be outside the **Show** time window, hidden by you, or filtered. Use **Add** to bring it in. |
| No sound | Click once on the page, and check **Audio** is ON in the natTrak box. |
| No flights appear, or changes do not save | Your key is missing, wrong or out of date. Keys last 90 days. Get a new one from [vnaaats.com/get-key](https://vnaaats.com/get-key). |
| "Your key is not known" | Copy the whole key again. The key belongs to the CID it was issued for, so connect with that same CID. |
| EuroScope closes when it starts | Check `server=https://vnaaats.com` (with https) in `vnaaats.cfg`. Install the Microsoft Visual C++ 2015-2022 Redistributable (x86) if the plugin will not load at all. |
| The radar screen shows wrong letters | `vNAAATS.ttf` is missing from the plugin folder. **Update now** in the app installs it. |
| "Update now" fails | Close EuroScope first. Windows will not let the app replace a plugin that is open. |
| The map is wrong or not oceanic | You have another sector file loaded. Use the Gander package from AeroNav. |
| The headphones (VACS) button stays grey | In VACS, open Advanced Settings and make sure **Enable remote control** is ticked, and that VACS is running. |

## Reporting a bug

Include the callsign, what you clicked, what you expected, what happened, the plugin version (the first line of `vNAAATS.log`) and the log file. Report it on [GitHub](https://github.com/garythms/vatsim-NAAATS-v2/issues) or to the Gander Oceanic team.

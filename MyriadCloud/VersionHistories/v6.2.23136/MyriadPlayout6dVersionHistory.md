# Myriad Playout Cloud v6 Version History

## v6.1.23136 15th May 2023

## v6.1.23089

### New Features/Changes:

**Log Playback:**
* If Myriad detects that it's approaching the end of an hour but the next hour has not been scheduled - typically within the last 6 or 7 items from the end of the log - the "Emergency End Of Log" scheduler will now attempt to schedule without waiting for the result, so the Log no longer has to stop and wait while that happens. If Log Playback gets to within 2 items of the end of the hour and that process is still runnig, then it WILL then stop and wait for that scheduling process to complete to prevent the station stalling at the end of the log and going off air.

**Myriad Schedule**
* There is a new option in **Station Settings** on the **Scheduler** tab to set Myriad to schedule "For the next 2 hours" - this will ensure that you always have at least 2 hours ahead in the log.
* The option to only schedule for the next 1 hour has been removed, and if you were set to this then you will now be set to schedule for the next 2 hours instead.

### The following issues have been fixed:

* **Log Playback**: If the next hour in the Scheduled Log has advert breaks, but there are no adverts to schedule for that particular hour, Myriad would keep trying to reschedule the ads for that next hour each time a segue happened during the last few items of the current hour.
* **Media Jump Buttons** The shared Media Jump buttons were not being automatically created for remote users to use.

## v6.1.23060
Initial public release.


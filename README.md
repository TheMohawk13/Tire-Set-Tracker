# Tire Set Tracker

Keep track of every tire set you use across a race weekend: how many dry and wet sets you have left, which sessions each set ran in, and how many laps are on it.

**Open it:** https://themohawk13.github.io/tire-set-tracker

Created by Ryne Hoover Transportation.

## Put it on your phone

1. Open the link above (Safari on iPhone, Chrome on Android).
2. Let the page finish loading while you have a connection. This saves it for offline use.
3. iPhone: tap **Share**, then **Add to Home Screen**. Android: open the browser menu, then **Install app** or **Add to Home Screen**.

After that it opens like an app and works without a signal.

## Quick start

1. **Create an event.** At the top, tap **New event**, type a name (for example "Road America"), and optionally pick the event date. **No date** clears it.
2. **Pick the event type.** Choose **Standard** (5 dry, 3 wet), **Endurance** (7 dry, 5 wet), or **Test** (no limit). The counters at the top follow the type you pick.
3. **Add your tire sets.** In the **Add a tire set** section, either:
   - tap **Add all missing sets** to create the full allocation at once (D1 to D5 and W1 to W3 for a standard weekend), or
   - add sets one at a time with a name, type (Dry or Wet) and **Laps already on it** for a set carried over from a previous event or test. Leave it at 0 for new tires.
4. **Log runs.** In **Log a run**, choose the tire set, the session (Practice 1, Practice 2, Qualifying or Race), enter the laps, and tap **Log run**. You can log the same set in more than one session.
5. **Check the board.** The Dry and Wet counters show how many sets you have used out of your allocation, with a dot for each. Each set card shows its total laps (including laps from before the weekend) and whether it is Unused, Not run yet, or Used. **By session** lists which sets ran in each session and how many laps.

## Fixing mistakes

- **Remove a run:** tap **Remove** next to it on the set card.
- **Delete a set or an event:** tap the delete button, then tap it again to confirm. If you don't tap again within a few seconds, it cancels.
- **Start an event over:** **Clear this event** (bottom of the page) removes all of its sets and runs. It asks for a second tap too.
- **Skip the opening screen:** tap anywhere on it.

## Past events

Every event is saved. Use the **Saved events** menu at the top to switch between them and look back at any weekend's sets, runs and laps.

## Where your data lives

Everything is saved on **your own device only**. Other people who open the link start with a blank copy and can't see your data, and you can't see theirs. Clearing your browser's website data erases it, and a different phone or browser will not have your events.

## Updating the site (for the site owner)

Upload the changed files to the repository, then raise the version number in `sw.js` (for example from `tire-tracker-v6` to `tire-tracker-v7`) so phones pick up the new version. iPhones save the home screen icon when it is added, so delete the old shortcut and add it again to see a new icon.

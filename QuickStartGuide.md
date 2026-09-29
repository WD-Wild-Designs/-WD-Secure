[WD] Secure Quick Start Version 0.9.0 Wild Designs
Get the system on, add one zone, and Arm it. That is enough to protect the land.

SETUP
    1. Rez it
Rez [WD] Secure on the parcel you own.
If the parcel is group owned, set the object to that group. Do not deed it to the group.
Touch the unit. You should see the main menu.
You do not add yourself. The owner is always a super admin.
    2. Add one zone
Tap Zones, then Add.
Range A sphere around the unit, clipped to this parcel. Linden Home sizes: 20 to 200 m. Mainland and private estate: Full Parcel, Custom Size up to 4096 m, or 20 to 100 m buttons.
Custom Zone Two boxes rez. Move Lo to the lowest left of the space. Move Hi to the highest right. Touch either box, tap Save, type a name.
Until at least one zone exists, the system does not watch anyone.
    3. Arm it
Back on the main menu, tap Arm.
Body color: Red = Disarmed Green = Armed Orange = Armed, but this object cannot eject. Fix parcel or group rights. Yellow = Lockdown. Mainland and private estate only. Emergency use only.
Hover version color: Green = this unit matches the current release Red = an update is available White = not checked yet
    4. Strangers
When someone not on a list enters a zone, the owner gets an arrival box: Visitor = may stay Temp Visitor = stay until they leave the region Restricted = remove now
Household guests can also be added later under Access.
    5. Useful extras
Get HUD Wear [WD] Secure: Owner HUD on this region. Touch it for Menu or Stats.
Update On the panel main menu (not the HUD). Checks the current release. Owners get a shop link if the unit is behind.
Housing On the panel main menu. Send Settings copies lists and zones to another [WD] Secure unit in this region. Same owner. Scripts stay on each unit.
Lockdown Mainland and private estate only. Griefing defense. Do not leave it on. Use Arm for daily protection.
Linden Home No Lockdown. No parcel ban list. No Full Parcel zone. Eject only. Range cap 200 m.
Need more detail? Open the Owner Guide.

WHAT IS IN 0.9.0
This is the first versioned Quick Start. It covers the live product as of 28 Sep 2026.
Features in this build
    • Label [WD] Secure or [WD] Secure: Feature.
    • Parcel-only scan. Watch is zones only.
    • Roles: Owner, Leader, Director, Visitor, Temp Visitor, Restricted.
    • Access lists with List, Add Near, Add Key, Remove by number.
    • Arrival box to the owner, grid-wide.
    • Enter and leave Direct on parcel with cached Display Name [username].
    • Warn IM to trespassers. Restart IM to staff.
    • Options page changes for Linden Home vs mainland / private estate.
    • Custom Zone Lo / Hi markers with Save and Delete Pair.
    • Range sizes, Full Parcel (not on Linden Home), Custom Size.
    • Zone List, Rename, Delete from Direct chat numbers.
    • Lockdown with confirm, yellow hover, restore previous Arm state. Hidden on Linden Home.
    • Owner HUD and Menu HUD. Get HUD. Auto-offer when added as Leader or Director.
    • HUD buttons: Menu, Stats, Close.
    • Panel buttons: Update and Housing (Owner / Leader).
    • GitHub version check. Clickable shop name plus Load URL for the owner.
    • Auto version check about every 3 hours. Hover green or red.
    • Housing Send Settings on the same region, same owner.
    • Updater rezzed on the ground. Loads Engine, Console, Access, Check. Gives Lo, Hi, both HUDs. Deletes itself.
    • Channel 77: menu, stats, update, allow, temp, ban, lh auto|on|off.
    • Stats: region, estate, avatars, FPS, dilation, last restart, list counts.

Bug fixes in this build
    • HUD no longer turns into a security unit when payload scripts run inside it.
    • Updater no longer remote-loads from an attachment. Rez on the ground.
    • Illegal load on a no-mod unit. Sold linkset stays Modify.
    • Stack-Heap Collision in Console. HTTP and Housing live in Check, not Console.
    • Double main menu on one touch. Touch debounce added.
    • Offline leave said unknown. Names are cached.
    • Maps slurl with %20 was cut in local chat. Shop link is now a short clickable name plus Load URL.
    • Version check slurl dropped on a second chat line. It is now in the same Update Check block.
    • Quick Start used to fire when the Updater loaded scripts. It now fires on a real rez only.
    • Keepers and Stewards words removed from menus. LSD keys still use wd.keepers and wd.stewards.
    • Parcel ban list and Lockdown cannot turn on for Linden Home.
    • Full Parcel zone blocked on Linden Home.
    • Marker hover tells you lowest left and highest right in plain words.

Known limits (not bugs)
    • Add by key / username is the weaker add path. Use Add Near or the arrival box.
    • Transfer cannot leave the region.

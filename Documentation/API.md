Loot Functions
CloseLoot([uiFailedFlag])
ConfirmBindOnUse()
ConfirmLootRoll(slot)   - Confirm a loot roll (NEW IN 1300)
GetLootMethod()   - Return the currently active lootMethod
GetLootRollItemInfo(rollId)
GetLootRollItemLink(rollId)
GetLootRollTimeLeft(rollid)
GetLootSlotInfo(slot)   - Returns icon path, item name, and item quantity for the item in the given loot window slot
GetLootSlotLink(slot)   - Returns an itemLink for the item in the given loot window slot
GetLootThreshold()   - Return the current loot threshold (for group/master loot)
GetMasterLootCandidate(index)   - Return the name of a player who is eligible to receive loot in master mode
GetNumLootItems()   - Returns amount of objects to loot (number)
GiveMasterLoot(slot,index)
IsFishingLoot()
LootSlot(slot)   - Used to confirm the looting of a BOP item
LootSlotIsCoin(slot)
LootSlotIsItem(slot)
RollOnLoot(rollId[, roll])   - Roll or pass on a loot event started by the game engine.
SetLootMethod("lootMethod"[, "masterPlayer" or threshold])   - Set the current loot method
SetLootPortrait()
SetLootThreshold(itemQuality)   - Set the threshold for group/master loot
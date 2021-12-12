Add my own separate foodtickcounter to HungerManager.update to tick over healing at the tail of the method.
If the tick >= 105 - (5 * hunger) && hunger > 0 {
Heal 1
Set tick to 0
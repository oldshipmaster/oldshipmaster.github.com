	新观察者模式
==================
我去
-
>fdsa
>fdsa
>fdsaf
>fdsa
>fdsa
>fdsa
>fdsa
>fdsa

	if (pet.getCooldowns().containsKey(cooldownKey)) {
			Cooldown cooldown = pet.getCooldowns().get(cooldownKey);
			if (System.currentTimeMillis() > cooldown.getStart() + cooldown.getDelay()) {
				//冷却时间已经结束
				return false;
			} else {
				return true;
			}
		}
		return false;
	}



[younghz的Markdown库1][1]
[younghz的Markdown库2][2]
[1]:https:://github.com/younghz/Markdown 
[2]:https:://github.com/younghz/Markdown 
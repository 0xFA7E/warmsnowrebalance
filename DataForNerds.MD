The following is some of the numerical scalings the game uses and what my mod actually changes value-wise. Note I am not sure what the ? value exactly affects. I suspect its either for fleshkin spawn or could be a boss modifier(which would explain why the boss modifier itself does virtually nothing in terms of scaling) Further investigation is required. 

# Original

HP difficulty modifiers(multiplied by enemy base HP
{
	Fine Snow
	{
		Prologue 1.1f,
		Chapter 1 1.1f,
		Chapter 2 1.05f,
		Chapter 3 1.05f,
		Chapter 4 1.1f,
		? 1.05f
	},
	Medium Snow
	{
		Prologue 1.3f,
		Chapter 1 1.7f,
		Chapter 2 2f,
		Chapter 3 2.3f,
		Chapter 4 3.3f,
		? 3f
	},
	Heavy Snow
	{
		Prologue 2.2f,
		Chapter 1 3f,
		Chapter 2 5f,
		Chapter 3 7f,
		Chapter 4 10f,
		? 8.3f
	},
	Snowstorm
	{
		Prologue 3f,
		Chapter 1 5.5f,
		Chapter 2 12f,
		Chapter 3 14f,
		Chapter 4 18f,
		? 15f
	},
	Blizzrad
	{
		Prologue 3.5f,
		Chapter 1 7f,
		Chapter 2 16f,
		Chapter 3 26f,
		Chapter 4 50f,
		? 36.5f
	}
};

# HP Rebalance Mod

{
	Heavy Snow
	{
		Prologue 1.8f,
		Chapter 1 2.3f,
		Chapter 2 2.4f,
		Chapter 3 3.8f,
		Chapter 4 5f,
		? 4.8f
	},
	Snowstorm
	{
		Prologue 2.3f,
		Chapter 1 2.5f,
		Chapter 2 3f,
		Chapter 3 5f,
		Chapter 4 8f,
		? 6.3f
	},
	Blizzrad
	{
		Prologue 2.5f,
		Chapter 1 3.3f,
		Chapter 2 5.5f,
		Chapter 3 7.5f,
		Chapter 4 8.5f,
		? 7.3f
	}
};

# Vampire Survivors Mode
Same as HP rebalance except for blizzrad
{
	Blizzrad
	{
		Prologue 1.5f,
		Chapter 1 2.0f,
		Chapter 2 2.2f,
		Chapter 3 3.5f,
		Chapter 4 4.5f,
		? 3.8f
	}
};

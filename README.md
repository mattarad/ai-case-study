# Uniy and Generative AI

## Unity Technologies has started implementing AI in the game development field. I believe that AI and ML will drastically change the gaming industry where we start seeing games become much more than what it is today; worlds that can be randomly generated through Generative AI and with full economies run by ML.

### Unity Technologies

- Incorporated on August 2, 2004

- Founders: David Helgason; Nicholas Francis; Joachim Ante

- Game Developers have always incorporated some sort of AI into games.

- The idea for Unity (originally called Over the Edge Entertainment) started when Francis posted a call for collaborators on an open-source shader compiler for the mac-based game developers. They originally released a video game, that didn't have much success, but realized they had developed a good game engine platform that developers could use to develope their own games. (Wikipedia)

- The company currently has several revenue streams from subscriptions tiers - each providing more utility to game developers, sales from their asset store, and add revenue.

  However, to date, the company is said that by 2018, Unity Technologies had raised over $600 Million and had a valuation of $3 Billion. (Wikipedia)
  On September 18, 2020 Unity Technologies launched its initial public offering (IPO) on the NYSE and raised more than $1.3 billion though its IPO at a $13.6 billion valuation. (Takahashi)

## Business Activities

- There is a lot of aspects that AI can touch in the gaming ecosystem, from asset(characters, items, scenes and props) to actually randomly generated levels, smarter AI enemies, improved computational path finding. They also have a suite of third party AI tools offered in the Unity Asset Store.

  The AI tools that Unity has released have focused on providing game developers with tools the speed up the game development process, as well as lower the cost of entry and over all game development costs.

- Intended customers are game developers and people interested in game developement.
  In an investor report from Unity, Unity has roughly 230,000 developers who make and operate over 750,000 games using the Unity Engine and the Unity Gaming Services portfolio of products.
  (Wallace)

- The tools that they offer have similarities with what their competitors offer. The difference would come in what language and game engine you start to use. Both Unity and Unreal provide a AI/ML plugin for developers to incorporate with ease.

- The most used AI/ML that Unity provides are their customizable Machine Learning Agents. See end of README.

"With Unity Machine Learning Agents (ML-Agents), you are no longer “coding” emergent behaviors, but rather teaching intelligent agents to “learn” through a combination of deep reinforcement learning and imitation learning." (Unity Machine)

## Landscape

- Gaming. Unity provides a Game Engine to streamline game development.

- AI/ML have been used to some degree in gaming since the beginning. From simple pathfinding alogrithms to now ML Agents and Generative AI building complex randomly generated levels.

- Unity's competitors are Unreal(C++), Godot(GDScript), and Bevy(Rust). The biggest by a long shot being Unreal.

## Results

- It is hard to quantify the business impact so far, aside from a bump in their stock price on the announcement. However, Unity provides a game engine that is used in over 70% of the most popular mobile games. (Packwood) With this solid market share in game development, they are in a prime position to capitalize on AI/ML to bring in more game developers, and lower the barrier to entry for game developement across the board.

- Monthly Active Game Developers and Subscribers

- There is a lot of debate on what Game Engine to develope using. Mostly coming down to preference. Unity's biggest competitor is Unreal Engine. Unreal is more well known for their 3D rendering and graphics - sometimes seen as overkill. Unity is known for its realitve simplicity to understand, and ease to develop games.

## Recommendations

- I would push Unity to focus on working with game asset creators to create AI generated content that game developers could use to create unique game assets at a lower cost, while still giving asset creators a revenue. Assets can be a costly entry cost to developing a game.

- The problem with this is that it could take a chunk of revenues from their asset store and anger their asset creators. It would have to be a partnership between Unity and the asset creators. With the competition from other game engines, this shift in game developement seems inevitable.

  Offering this product and service to game developers would give indie game developers a major leg up in creating unique games.

- This product would utilize Artificial General Intelligence (AGI)

- Because they would give low funded game developers a huge leg up in development.

In this code, the function update is called every frame on each AI Enemy character, checking if the AI is aggrevated or can attack the player or has recently seen the player. If IsAggrevated and CanAttack(player) return false, and SuspisionBehavoir() returns false, then the AI will go back to PatrolBehavior()

```C#
void Update()
{
  if(IsAggrevated() && fighter.CanAttack(player))
  {
      AttackBehavior();
  }
  else if(timeSinceLastSawPlayer < suspisionTime)
  {
      SuspisionBehavoir();
  }
  else
  {
      PatrolBehavior();
  }
}
```

Below is a video of a package provided by Unity built with Python to develop Machine Learning Agents, spoken above. ML Agents use a reward based system to "learn" that the goal of the game is to find the gold ball. ML Agents get rewarded for collecting gold balls while losing points for hitting walls.

https://github.com/mattarad/ai-case-study/assets/15133901/3dc042a3-8faf-4617-ad18-c4cd74c6c586

# Uniy and Generative AI

## Unity Technologies has started implementing AI in the game development field. I believe that AI and ML will drastically change the gaming industry where we start seeing Games become much more that what they are today, but worlds that can be randomly generated through Gen AI and with full economies run by ML.

### Unity Technologies

- When was the company incorporated?
  Incorporated on August 2, 2004

- Who are the founders of the company?
  Founders: David Helgason; Nicholas Francis; Joachim Ante

- How did the idea for the company (or project) come about?
  The idea for Unity (originally called Over the Edge Entertainment) started when Francis posted a call for collaborators on an open-source shader compiler for the mac-based game developers. They originally released a video game, that didn't have much success, but realized they had developed a good game engine platform that developers could use to develope their own games. (Wikipedia)

- How is the company funded? How much funding have they received?
  The company currently has several revenue streams from subscriptions tiers - each providing more utility to game developers, sales from their asset store, and add revenue.

  However, to date, the company is said that by 2018, Unity Technologies had raised over $600 Million and had a valuation of $3 Billion. (Wikipedia)
  On September 18, 2020 Unity Technologies launched its initial public offering (IPO) on the NYSE and raised more than $1.3 billion though its IPO at a $13.6 billion valuation. (Takahashi)

## Business Activities

- What specific problem is the company or project trying to solve?
  There is a lot of aspects that AI can touch in the gaming ecosystem, from asset(characters, items, scenes and props) to actually randomly generated levels, smarter AI enemies, improved computational path finding. They also have a suite of third party AI tools offered in the Unity Asset Store.

  The AI tools that Unity has released have focused on providing game developers with tools the speed up the game development process, as well as lower the cost of entry and over all game development costs.

- Who is the company's intended customer? Is there any information about the market size of this set of customers?
  Intended customers are game developers and people interested in game developement.
  In an investor report from Unity, Unity has roughly 230,000 developers who make and operate over 750,000 games using the Unity Engine and the Unity Gaming Services portfolio of products.
  (Wallace)

- What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)
  The tools that they offer have similarities with what their competitors offer. The difference would come in what language and game engine you start to use.

- Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing&mdash;you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)
  The most used AI/ML that Unity provides are their Machine Learning Agents. These agents can increase

"With Unity Machine Learning Agents (ML-Agents), you are no longer “coding” emergent behaviors, but rather teaching intelligent agents to “learn” through a combination of deep reinforcement learning and imitation learning." (Unity Machine)

## Landscape

- What field is the company in?
  Gaming

- What have been the major trends and innovations of this field over the last 5&ndash;10 years?
  AI/ML have been used to some degree in gaming since the beginning. From simple pathfinding alogrithms to now ML Agents and Generative AI building complex randomly generated levels.

- What are the other major companies in this field?
  Unreal(C++), Godot(GDScript), and Bevy(Rust)

## Results

- What has been the business impact of this company so far?
  It is hard to quantify the business impact so far, aside from a bump in their stock price on the announcement. However, Unity provides a game engine that is used in over 70% of the most popular mobile games. (Packwood) With this solid market share in game development, they are in a prime position to capitalize on AI/ML to bring in more game developers, and lower the barrier to entry for game developement across the board.

- What are some of the core metrics that companies in this field use to measure success? How is your company performing based on these metrics?
  Monthly Active Game Developers and Subscribers

- How is your company performing relative to competitors in the same field?
  There is a lot of debate on what Game Engine to develope using. Mostly coming down to preference. Unity's biggest competitor is Unreal Engine. Despite Unreal being more renown for their 3D rendering, Unity's simplicity and ease of use allows for a larger audience to enter into game developement.

## Recommendations

- If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)
  I would push Unity to focus on working with game asset creators to create AI generated content that game developers could use to create unique game assets at a lower cost, while still giving asset creators a revenue. Assets can be a costly entry cost to developing a game.

- Why do you think that offering this product or service would benefit the company?
  The problem with this is that it could take a chunk of revenues from their asset store and anger their asset creators. It would have to be a partnership between Unity and the asset creators. With the competition from other game engines, this shift in game developement seems inevitable.

  Offering this product and service to game developers would give indie game developers a major leg up in creating unique games.

- What technologies would this additional product or service utilize?
  AGI

- Why are these technologies appropriate for your solution?
  Because they would give low funded game developers a huge leg up in development.

in this code, the function update is called every frame on each AI Enemy character, checking if the AI is aggrevated or can attack the player or has recently seen the player. If IsAggrevated and CanAttack(player) return false, and SuspisionBehavoir() returns false, then the AI will go back to PatrolBehavior()

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

Below is a video of a package provided by Unity built with Python to develop Machine Learning Agents. ML Agents use a reward based system to "learn" that the goal of the game is to find the gold ball. ML Agents get rewarded for collecting gold balls while losing points for hitting walls.

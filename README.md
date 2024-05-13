# TITLE

## Overview and Origin

- Name of company

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
  On September 18, 2020 Unity Technologies launched its initial public offering (IPO) on the NYSE and raised more than $1.3 billion though its IPO at a $13.6 billion valuation.
  (https://venturebeat.com/business/unity-technologies-raises-more-than-1-1-billion-in-ipo-at-12-1-billion-valuation/)

## Business Activities

- What specific problem is the company or project trying to solve?
  There is a lot of aspects that AI can touch in the gaming ecosystem, from asset(characters, items, scenes and props) to actually randomly generated levels, and smarter AI enemies. They also have a suite of third party AI tools offered in the Unity Asset Store.
  The AI tools that Unity has released have focused on providing game developers with tools the speed up the game development process, as well as lower the cost of entry and over all game development costs.

- Who is the company's intended customer? Is there any information about the market size of this set of customers?
  Intended customers are game developers and people interested in game developement.
  In an investor report from Unity, Unity has roughly 230,000 developers who make and operate over 750,000 games using the Unity Engine and the Unity Gaming Services portfolio of products.
  (https://investors.unity.com/news/news-details/2022/Gaming-Poised-to-Continue-Accelerated-Growth-According-to-Unity-Gaming-Report-2022/default.aspx#:~:text=The%20Gaming%20Report%202022%20draws,Gaming%20Services%20portfolio%20of%20products.)

- What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)
  The tools that they offer have similarities with what their competitors offer. The difference would come in what language and game engine you start to use.

- Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing&mdash;you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)

## Landscape

- What field is the company in?
  Gaming

- What have been the major trends and innovations of this field over the last 5&ndash;10 years?

- What are the other major companies in this field?
  Unreal(C++), Godot(GDScript), and Bevy(Rust)

## Results

- What has been the business impact of this company so far?
  Unity provides a game engine that is used in over 70% of the most popular mobile games.
  (https://atelier.net/insights/scene-from-the-matrix-awakens-an-unreal-engine-5)

Most likely due to how seamless Unity makes it for game developers to deploy to multiple platforms.

- What are some of the core metrics that companies in this field use to measure success? How is your company performing based on these metrics?

- How is your company performing relative to competitors in the same field?

## Recommendations

- If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)
  I would push Unity to focus on working with game asset creators to create AI generated content that game developers could use to create unique game assets at a lower cost, while still giving asset creators a revenue. Assets can be a costly entry cost to developing a game.

- Why do you think that offering this product or service would benefit the company?
  The problem with this is that it could take a chunk of revenues from their asset store and anger their asset creators. It would have to be a partnership between Unity and the asset creators.

However, offering this product and service to game developers would give indie game developers a major leg up in creating unique games.

- What technologies would this additional product or service utilize? AGI

- Why are these technologies appropriate for your solution?

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

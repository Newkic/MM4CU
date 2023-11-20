# MMLSCU:A Dataset for Multimodal Multi-domain Live Streaming Comment Understanding
<!-- **MMLSCU:A Dataset for Multimodal Multi-domain Live Streaming Comment Understanding** -->

## 1.Dataset
<p align="center" width="100%">
<a target="_blank"><img src="figs/sample.PNG" alt="MM4CD" style="width: 80%; min-width: 200px; display: block; margin: auto;"></a>
</p>

### 1.1 Four Live Streaming Comment Understanding tasks
  - viewer comment intent detection 
  - intent cause mining 
  -  viewer comment explanation 
  -  streamer policy suggestion.
### 1.2 dataset samples.
Here we give a sample annotation of some data sets, where "0:00:01" represents the time the comment was posted, the number in [] is the emoji id, and 'last last last one' is the comment content.
```
[
    [
        [
            "0:00:01",
            [],
            "last last last one"
        ],
        "hope",
        "Reason for the intent: The viewer wants to express optimism and expectation for the streamer;",
        "Explanation of the comment: The viewer is saying this is their last attempt or last prediction, encouraging the streamer to succeed this time.",
        "Suggestion: Boost Audience Interaction"
    ],
    [
        [
            "0:00:01",
            [],
            "X"
        ],
        "unlike",
        "Reason for the intent: The viewer wants to show disapproval or disagreement with something happening in the stream;",
        "Explanation of the comment: The viewer uses the letter \"X\" to symbolize that they are not in favor of and do not like the action made by the streamer in the game.",
        "Suggestion: Boost Audience Interaction"
    ],
    [
        [
            "0:00:01",
            [],
            "KEKW"
        ],
        "like",
        "Reason for the intention: The viewer wants to express amusement and enjoyment of a funny moment in the stream;",
        "Explanation of the comment: The viewer uses the Twitch emote \"KEKW\" which represents laughter, indicating that they found something in the stream amusing and entertaining.",
        "Suggestion: None"
    ],
    [
        [
            "0:00:01",
            [
                "425618"
            ],
            "LUL"
        ],
        "like",
        "Reason for the intention: The viewer is entertained by what is happening in the stream.",
        "Explanation of the comment: LUL is the shorthand for 'laughing out loud'. It's a popular emote on Twitch used when something amusing happens on the stream.",
        "Suggestion: None"
    ],
    [
        [
            "0:00:01",
            [],
            "x"
        ],
        "unlike",
        "Reason for the intention: The viewer dislikes or disagrees with what is happening in the stream.",
        "Explanation of the comment: 'x' is typically used in digital communication to symbolize a wrong decision, error, or something negative. In this context, the viewer is expressing their disapproval or negative sentiment towards the current content.",
        "Suggestion: Boost Audience Interaction"
    ],
    [
        [
            "0:00:01",
            [],
            "Bites the Dust no. 29"
        ],
        "hope",
        "Reason for the intention: The viewer is excited and hopeful for what comes next in the stream, relating to a desired event.",
        "Explanation of the comment: 'Bites the Dust' here means to have a big defeat. 'Bites the Dust no. 29' refers to a specific scenario in the streamed game that the viewer is hoping to see.",
        "Suggestion: Boost Audience Interaction"
    ],
    [
        [
            "0:00:01",
            [
                "425618"
            ],
            "LUL"
        ],
        "like",
        "Reason for the intention: The viewer wants to express their amusement and laughter at what is happening now.",
        "Explanation of the comment: LUL is a twitch emote used to indicate laughter or amusement.",
        "Suggestion: None"
    ],
    [
        [
            "0:00:01",
            [],
            "Last one"
        ],
        "hope",
        "Reason for the intention: The viewer wants the streamer to know they're rooting for them.",
        "Explanation of the comment: 'Last one' could be seen as encouragement of saying that they believe the streamer can make it through one more round, level, or attempt.",
        "Suggestion: Boost Audience Interaction"
    ],
]
```
## 2.Model
MM4CU:MultiModal Four Comment Understanding Tasks model
<p align="center" width="100%">
<a target="_blank"><img src="figs/model.PNG" alt="MM4CD" style="width: 80%; min-width: 200px; display: block; margin: auto;"></a>
</p>










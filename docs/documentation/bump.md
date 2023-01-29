---
title: Bump Setup
description: The Bump setup documentation
sidebar_position: 2
---

import Button from '../../src/components/Button';
import {
  DiscordInteraction,
  DiscordMessage,
  DiscordMessages,
  DiscordMention,
  DiscordEmbed,
  DiscordEmbedField,
  DiscordEmbedFields,
} from "discord-message-components/packages/react";
import "discord-message-components/packages/react/dist/style.css";

:::caution Warning

To use any of these commands, you need to have **Manage Guild** permissions.

:::

## Bump Setup Commands

:::note

Some premium commands may no longer work due to the new discord developer TOS update.

:::

| Usage | Description | Premium |
| ----------- | ----------- | ----------- |
| <code><DiscordMention>Vertex Bump</DiscordMention> setdesc/description &lt;decription&gt</code> | Set your servers decription (Make sure to take out your server link) | False |
| <code><DiscordMention>Vertex Bump</DiscordMention> setinvite &lt;channel&gt</code> | Sets your server invite that will be part of your servers bump | False |
| <code><DiscordMention>Vertex Bump</DiscordMention> setchannel &lt;channel&gt</code> | Sets the channel where all discord bumps from other servers will go | False |
| <code><DiscordMention>Vertex Bump</DiscordMention> setbanner &lt;banner-link&gt</code> | Sets your servers bump banner | <premium>True</premium> |
| <code><DiscordMention>Vertex Bump</DiscordMention> setcolor &lt;HEX-code&gt</code> | Sets your servers bump embed color | <premium>True</premium> |

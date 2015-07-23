---
published: true
title: Secrets of the Amazon - Boto3 & Running DynamoDB locally
layout: post
---
If you are trying to roll with a DynamoDB locally, and have recently tried roll with Boto3, a neat little python library put out for AWS for DynamoDB - you might have come across a problem.

You *used* to be able to connect to a local DynamoDB instance, but now the documentation sucks and doesn't tell you about a secret connection string.

Lets say you turn to amazon for answers:

Well, here is what you'll get:

<a href="http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/TicTacToe.Phase1.html">Tic Tac Toe</a>

That's all well and good, but its also not using boto3 now is it?

<script src="https://gist.github.com/mehmetcodes/b05961cf1e11310479fd.js"></script>

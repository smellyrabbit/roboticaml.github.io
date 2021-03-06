---
title: What Is Machine Learning?
layout: posts
---

![Robot toy](/img/robot-toy.jpeg) <br />
# What Is Machine Learning?
Artificial intelligence, machine learning, deep learning, neural networks. These are all hot topics and they carry with them a lot of hype. Here is a very brief explanation of each term.

## Artificial Intelligence
Artificial intelligence, or AI, is the concept of giving computers the responsibility to make decisions that would normally be made by human beings.  Often, the decision making process is not obvious and the rules that power AI may appear fuzzy. 
AI can be created using Machine Learning, where computers work out the rules, or knowledge engineering.  Knowledge engineering depends on people carefully trying to articulate their domain-specific knowledge and turning into knowledge maps and rules.  This approach can prove very effective for simple problems, but will inevitably miss hidden patterns that the domain experts have not noticed.

## Machine Learning
All Machine Learning (ML) falls into the broader class of Artificial Intelligence, but ML differs from knowledge engineering because it moves the responsibility of discovering rules from people to computers.  Algorithms trawl through large volumes of data, generating and trying out different rules until it finds some that work for most or all of the data.  Often, these rules are subtle and concealed.  It may be that counter-intuitive rules, which could never be recognised by domain experts, emerge from ML.  Machine learning typically requires significant computational power to work through the problems, which is why the job of teaching the models is often delegated to the cloud. 
The most advanced tools for automating machine learning, such as DataRobot, go a step further to expose the meaning behind the rules.  Transparency of the models makes a real difference in the level of trust you may afford to your AI as it helps to demonstrate regulatory compliance and to reveal how and why models behave generally and for specific data.

![Big Data](/img/servers.jpeg) <br />

## Linear Regression
The simplest form of machine learning is finding a line of best fit through the data points.  This may be a single straight line throughout the entire sample, or a sequence of short, straight lines that may take on the appearance of a curve.  Linear regression can be an efficient way to make predictions where there are not many features or an excess of anomalous or outlying values in the data.

## Decision Trees
One of the most common and effective modelling approaches in machine learning is to create decision trees.  Decision trees are computer-generated questions about the data.  Each question filters out possible branches until there are no more questions left to ask.  When there are no more questions, the algorithm has reached a leaf and that leaf holds the prediction.  Think of decision trees as turning your business objective into a game of Twenty Questions.  ML works out what all of the different questions may be and aims to minimise the number of branches necessary to reach each leaf.  

## Neural Networks
Neural networks are a different approach to modelling prediction problems.  Their mechanism is very similar to that of the vertebrate brains.  A network of simulated brain cells or neurons joins neurons to each other.  Data is fed to the neurons on the _input layer._  The input is then fed across each connection from each input node to a _hidden layer _where each incoming signal is multiplied by the strength or weight of the connection. For each node where the sum total of the connected inputs is large enough, a signal is sent from that hidden node to the _output layer. _ The nodes of output layer repeat the same process of summing the weighted connections to see if its threshold is breached.  
During training, the connection weights are increased whenever the resulting output matches the desired result, and weakened when the output is incorrect.  Over time, the connections become able to predict outcomes based on the combinations of input values.

## Deep Learning
Deep learning is a special type of neural network that contains multiple hidden layers and can be very effective at solving problems like image recognition. Each layer acts as an abstraction from the data and can be thought of as performing a new operation.  For an image recognition problem, the first hidden layer may detected all of the edges in a picture and the second layer recognise geometric shapes from the edges. A third layer may then effectively match combinations of shapes to the distinct items it has been taught, such as faces.

![Big Data](/img/wooden-robot.jpeg) <br />

## The Rise of the Machines
Some people worry that generalised artificial intelligence is a threat to humanity.  We are still a long way from generalised AI or anything that resembles thought or consciousness.  Outside the movies, AI is predominantly domain-specific, solving clear-cut, narrow problems.  Robotica is focused on domain-specific ML to solve real world problems with science fact.

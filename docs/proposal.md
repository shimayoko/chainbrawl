# ChainBrawl

_Fully on-chain autobattler where every fight is computed and verified on Solana_

## Summary

ChainBrawl is a PvP autobattler where character stats, battle logic, and randomness all live on-chain, letting players truly own their fighters as NFTs and trust that outcomes can't be manipulated. Players mint a fighter NFT, auto-battle against others using deterministic on-chain logic plus VRF-based randomness, and climb a ranked ladder for token rewards.

## Target users

Solana-native gamers and NFT collectors who want provably fair, ownable PvP games

## Problem

Most 'blockchain games' just put a shop on-chain while the actual gameplay and outcomes happen on centralized servers, so players can't verify fairness.

## Solution

ChainBrawl moves the battle resolution logic itself on-chain using a program that combines fighter stats with Switchboard VRF randomness, producing a fully verifiable and replayable outcome.

## MVP features

- Mint a fighter NFT with randomized on-chain stats
- On-chain battle resolution program using VRF for fair randomness
- Ranked ladder with on-chain leaderboard PDA
- Stake SOL/tokens to enter matches with on-chain escrow payout
- Simple web client to view replay of each on-chain battle

## Chains

Solana

## Tech

Anchor, Switchboard VRF, Solana Program Library (SPL), Metaplex NFT, React, Solana Web3.js

## Category

Gaming

## Why now

Solana's cheap, fast transactions finally make it feasible to run real-time game logic and randomness fully on-chain without ruining UX.

## Roadmap

- Add matchmaking and seasonal tournaments with prize pools
- Expand to multiplayer team battles (3v3)
- Open an SDK so other studios can plug in on-chain battle resolution

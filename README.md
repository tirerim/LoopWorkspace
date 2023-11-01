# Attention please!

FreeAPS is no longer supported.

* branch freeaps: limited to Xcode 14 and iOS 16
* branch freeaps_dev: modified to build with Xcode 15
* other branches in this repository are tied to LoopKit (Loop 3)

# LoopWorkspace - How To Build

## Clone

This repository uses git submodules to pull in the various workspace dependencies.

To manually clone this repo:

For freeaps, copy and paste this into the terminal

```
export BRANCH_NAME="freeaps"
```

For freeaps_dev, copy and paste this into the terminal

```
export BRANCH_NAME="freeaps_dev"
```

Then issue the clone command.

```
git clone --branch=$BRANCH_NAME --recurse-submodules https://github.com/loopnlearn/LoopWorkspace
```

## Open

Change to the cloned directory and open the workspace in Xcode:

```
cd LoopWorkspace
xed .
```

## Build

Select the "Loop (Workspace)" scheme (not the "Loop" scheme) and Build, Run, or Test.

<a href="/docs/scheme-selection.png"><img src="/docs/scheme-selection.png?raw=true" alt="Image showing how to select the Loop (Workspace) scheme in Xcode" width="400"></a>

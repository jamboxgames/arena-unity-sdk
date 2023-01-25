# Version 2.3.1 (25 Jan 2023)
1. Added Filter for GetTournamentDetail APIs

# Version 2.3.0 (9 Jan 2023)
1. Added Leaderboard APIs

# Version 2.2.7 (22 May 2022)
1. Added Scoring Mode and Sorting fields in Tournaments details.
2. Handling Tournament types of Sorting order Increasing in Realtime Leaderboard Widget.
    ```
    public void InitializeRealtimeLeaderboard(List<leaderBoardData> data, bool scrollable, int NoOfRecordsToShow, bool disappearingLB = false, bool fullLeaderboard = true, ESortOrder sortOrder = ESortOrder.ESortOrderDescending)
    ```
4. Addition of Landscape UI with the package.

# Version 2.2.5 (6 May 2022)
1. Added multiple options(best, incremental, latest) for how your score is calculated in the leaderboard. 
2. Tournaments can be joined by Rewarded Video Ads.
3. Matchmaking - Tournaments can have multiple leaderboards based on some user variable ranges.
4. Testing Users functionality
5. Developers can set up devices as test devices identified by GAID or IDFA
6. Developers can mark test only flags while creating events so that it is visible only for test devices.


# Version 2.2.1
Custom UI option for developers to use the Arena UI to customize as per their game. 
For creating Custom UI :

1. Copy All the prefabs from Assets/JamboxPackage/Jambox Tourney/Resources/Theme/ to Assets/Resources/JamboxArenaUI
2. Set "Active Theme" variable in Jambox SDK params as "Custom Theme"


# Version 2.1.8

1. Expose API to be called directly from the Game code without need of showing Arena UI.
2. Separate Error Callbacks functions for all the APIs for improved error messaging.
3. New Update profile method for developers to use to save User avatar.


# Version 2.1.0
1. New User Avatar selections - Human Avatar. Profile Screen has two tabs now for selecting avatar images
2. Control to developer to open desired arena event tabs when opening Arena UI (tournament/Duels/Friendly). Currently Tournament is open by default.
3. Show notification dialog for unclaimed Rewards tournaments when users open the Arena UI everytime. 
4. New Realtime Rank showing widget for developers to show on gameplay screen. Widget has an option for fixed and disappearing behaviour. 
5. Replay Data interval time string conversion bug. Some duels replay data were not showing the



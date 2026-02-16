flowchart TD

%% ---- LEVEL 1 ----
subgraph Level1["Start"]
A1["1 Clear Stadium Site\n70d"]
end

%% ---- LEVEL 2 ----
subgraph Level2["Initial Work"]
A2["2 Demolish Existing Building\n30d"]
A4["4 Drive Support Piling\n120d"]
end

%% ---- LEVEL 3 ----
subgraph Level3["Setup & Prep"]
A3["3 Set Up Construction Site\n70d"]
A5["5 Pour Lower Concrete Bowl\n120d"]
end

%% ---- LEVEL 4 ----
subgraph Level4["Main Construction"]
A6["6 Pour Main Concourse\n120d"]
A7["7 Install Playing Field\n90d"]
A8["8 Construct Upper Steel Bowl\n120d"]
A15["15 Build Roof Supports\n90d"]
end

%% ---- LEVEL 5 ----
subgraph Level5["Secondary Tasks"]
A9["9 Install Seats\n140d"]
A10["10 Build Luxury Boxes\n90d"]
A11["11 Install Jumbotron\n30d"]
A12["12 Stadium Infrastructure\n120d"]
A16["16 Construct Roof\n180d"]
A17["17 Install Roof Tracks\n90d"]
end

%% ---- LEVEL 6 ----
subgraph Level6["Final Construction"]
A13["13 Construct Steel Canopy\n75d"]
A18["18 Install Roof\n90d"]
end

%% ---- LEVEL 7 ----
subgraph Level7["Finishing"]
A14["14 Light Installation\n30d"]
end

%% ---- LEVEL 8 ----
subgraph Level8["Inspection & Cleanup"]
A19["19 Inspection\n20d"]
A20["20 Cleanup\n21d"]
end

%% ---- DEPENDENCIES ----
A1 --> A2
A1 --> A4
A2 --> A3
A4 --> A5
A3 --> A6
A5 --> A6
A3 --> A7
A5 --> A7
A3 --> A8
A5 --> A8
A6 --> A9
A8 --> A9
A6 --> A10
A8 --> A10
A6 --> A11
A8 --> A11
A6 --> A12
A8 --> A12
A5 --> A15
A15 --> A16
A15 --> A17
A16 --> A18
A17 --> A18
A9 --> A13
A13 --> A14
A7 --> A19
A10 --> A19
A11 --> A19
A12 --> A19
A14 --> A19
A18 --> A19
A19 --> A20

%% ---- HIGHLIGHT CRITICAL PATH ----
style A1 fill:#ff4d4d,color:#fff
style A4 fill:#ff4d4d,color:#fff
style A5 fill:#ff4d4d,color:#fff
style A6 fill:#ff4d4d,color:#fff
style A8 fill:#ff4d4d,color:#fff
style A9 fill:#ff4d4d,color:#fff
style A13 fill:#ff4d4d,color:#fff
style A14 fill:#ff4d4d,color:#fff
style A19 fill:#ff4d4d,color:#fff
style A20 fill:#ff4d4d,color:#fff

# sanjana

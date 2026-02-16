```mermaid
flowchart TD
A1["1 Clear Site\n70d"] --> A4["4 Drive Piling\n120d"]
A1 --> A2["2 Demolish\n30d"]
A2 --> A3["3 Setup Site\n70d"]
A4 --> A5["5 Lower Bowl\n120d"]
A3 --> A6["6 Main Concourse\n120d"]
A5 --> A6
A3 --> A7["7 Playing Field\n90d"]
A5 --> A7
A3 --> A8["8 Upper Steel Bowl\n120d"]
A5 --> A8
A6 --> A9["9 Install Seats\n140d"]
A8 --> A9
A6 --> A10["10 Luxury Boxes\n90d"]
A8 --> A10
A6 --> A11["11 Jumbotron\n30d"]
A8 --> A11
A6 --> A12["12 Infrastructure\n120d"]
A8 --> A12
A5 --> A15["15 Roof Supports\n90d"]
A15 --> A16["16 Construct Roof\n180d"]
A15 --> A17["17 Roof Tracks\n90d"]
A16 --> A18["18 Install Roof\n90d"]
A17 --> A18
A9 --> A13["13 Steel Canopy\n75d"]
A13 --> A14["14 Light Installation\n30d"]
A7 --> A19["19 Inspection\n20d"]
A10 --> A19
A11 --> A19
A12 --> A19
A14 --> A19
A18 --> A19
A19 --> A20["20 Cleanup\n21d"]

%% Highlight Critical Path
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

This repository contains a demonstration of a common error in COBOL programs involving array out-of-bounds access. The `bug.cob` file shows the erroneous code, while `bugSolution.cob` provides the corrected version.  The issue arises from the lack of bounds checking in a loop that populates an array.  The solution introduces a check to prevent access beyond the defined array limits, thus enhancing the robustness of the program.  This example highlights the importance of careful array handling in COBOL to avoid runtime errors and data corruption.
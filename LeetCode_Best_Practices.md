LeetCode Editor Best Practices

1. Follow the Function Signature – Don’t Use 'main()'
LeetCode already defines a 'main()' internally. Only implement the required method.
✅ Do this:
public List<List<Integer>> threeSum(int[] nums) {
    // your logic
}
❌ Avoid:
public static void main(String[] args) {
    // Won't be called
}

2. Use Custom Testcases Smartly
Click on 'Testcase > Use Custom Testcase'. Add edge/stress cases:
- Empty input
- Single element
- Large input
- Repeated or sorted arrays

3. Write Clean, Modular Code
Use helper methods, meaningful variable names, and inline comments.
Example:
int[] countFreq(int[] nums) {
    int[] freq = new int[101];
    for (int num : nums) {
        freq[num]++;
    }
    return freq;
}

4. Use Console Output for Debugging
Use System.out.println() to debug:
System.out.println("i = " + i);
Remove debug lines before submission.

5. Handle Edge Cases at the Top
For arrays:
if (nums == null || nums.length < 3) return new ArrayList<>();
For strings:
if (s == null || s.isEmpty()) return false;

6. Run Small Tests Before Submitting
Use 'Run' on custom tests before final submit to avoid silly runtime errors.

7. Watch Execution Time and Memory
After submission, check runtime and memory stats. Aim for clean and optimal code.

8. Format Code (Manually if Needed)
Use proper indentation and consistent spacing. Java tip: Ctrl + A then Tab.

9. Use Comments to Outline Plan (Temporarily)
Helps organize logic:
// Step 1: Sort
// Step 2: Apply two pointers

10. Copy Final Code to Your Repo/Tracker
Save your AC solutions with:
- Problem name
- Difficulty
- Time/space complexity
- Insights or learnings

Pro Tip: Use Interview Simulation Mode
In Settings (⚙), enable:
- Interview Mode UI
- Hide Testcases
- Hide Tags & Hints
-

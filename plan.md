1. **Modify `ModelManagerViewModel.kt`:**
   - Update `getActiveCustomTasks()` to filter the injected tasks and return *only* the one corresponding to `LLM_AGENT_CHAT`.
2. **Verify changes:**
   - Use `grep` or `cat` to ensure the modifications to `ModelManagerViewModel.kt` were written correctly.
3. **Complete pre-commit steps:**
   - Complete pre commit steps to ensure proper testing, verification, review, and reflection are done.
4. **Test & Submit:**
   - Run tests `./gradlew test` in `Android/src/`
   - Submit the change.

<script>
	import TaskList from "$lib/TaskList.svelte";
	import Timer from "$lib/Timer.svelte";

	var tasks = ["Task 1", "Task 2", "Task 3"]
	var timer = 2930948
</script>

<!-- Task List -->
<div class="flex flex-row">
	<Timer {timer}></Timer>
	<TaskList {tasks}></TaskList>
</div>

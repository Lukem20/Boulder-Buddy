<script>
    import ProjectItem from "./ProjectItem.svelte";
    export let projects = [];

    console.log(projects);
</script>

{#each projects as project (project.id)}
    <ProjectItem item={project} />
{/each}
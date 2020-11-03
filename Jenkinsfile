#!groovy
properties([
    parameters([
        booleanParam(defaultValue: true,
                     description: 'Cancel the rest of parallel stages if one of them fails and return status immediately',
                     name: 'failFast'),
        string(
            trim: true,
            defaultValue: 'akladiev/github_get_changed_files',
            name: 'library_version')
    ])
])

dldtPipelineEntrypoint(this)

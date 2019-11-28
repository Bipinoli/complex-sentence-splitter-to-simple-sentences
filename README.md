# About
This package splits a complex text into simple sentences.

Examples:
    
    input: My brother and sister, who are the members of the association are working hard.
    output: ['my sister are working hard .', 'my brother are working hard .', 'my brother are the members of the association', 'my sister are the members of the association']

    input: My father, who is a President, is an honest man.
    output: ['my father , is an honest man .', 'my father is a president']

    input: The pricing, service and location is just perfect but its too bad we cannot depends on its availability.
    output: ['The pricing , is just perfect', 'its too bad we can not depends on its availability .', 'The service , is just perfect', 'The location , is just perfect']

    input: Ram called his friend Hari. They both liked the place but didn't like the price attached.
    output: ['Ram called his friend Hari .', "did n't like the price attached .", 'They both liked the place']

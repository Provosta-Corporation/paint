<!DOCTYPE html>
/* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    color: #333;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
}

.header {
    background: #0056a5;
    color: white;
    padding: 2rem 1rem;
    text-align: center;
}

.header h1 {
    margin: 0;
    font-size: 2.5rem;
}

.header p {
    margin: 0.5rem 0 1rem;
}

.header .btn {
    background: #ffcc00;
    color: #333;
    padding: 0.75rem 1.5rem;
    text-decoration: none;
    border-radius: 5px;
}

.why-choose-us, .services, .pricing, .testimonials, .contact {
    padding: 2rem 1rem;
    background: #f9f9f9;
    margin: 1rem 0;
}

.why-choose-us h2, .services h2, .pricing h2, .testimonials h2, .contact h2 {
    text-align: center;
    margin-bottom: 1rem;
}

.features {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
}

.feature {
    flex: 1 1 calc(50% - 1rem);
    background: white;
    padding: 1rem;
    border: 1px solid #ddd;
    border-radius: 5px;
}

.pricing .plans {
    display: flex;
    gap: 1rem;
}

.plan {
    flex: 1;
    background: white;
    padding: 1rem;
    border: 1px solid #ddd;
    border-radius: 5px;
}

blockquote {
    background: #eee;
    padding: 1rem;
    border-left: 5px solid #0056a5;
    margin: 1rem 0;
}

footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 1rem;
}
